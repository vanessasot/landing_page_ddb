<template>
    <div class="modal" id="modal">
        <div class="modal_content">
            <div class="modal_header">
                <h1>Modal</h1>
                <span class="modal_close" @click="hide()">&times;</span>
            </div>
            <div class="modal_body">
                <slot />
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Modal',
  methods: {
    show () {
      const modal = document.getElementById('modal')
      modal.classList.add('show')
    },
    hide () {
      const modal = document.getElementById('modal')
      modal.classList.remove('show')
    }
  }
}
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.modal {
  position: fixed;
  display: flex;
  align-items: center;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: rgba(0, 0, 0, 0.4);
  visibility: hidden;
  opacity: 0;
  transition: opacity 0.4s ease-in-out, visibility 0.4s ease-in-out, transform 0.4s ease-in-out;
}

.modal.show {
  visibility: visible;
  opacity: 1;
}

.modal.show .modal_content {
  visibility: visible;
  opacity: 1;
  transform: scale(1);
}

.modal_content {
  min-width: 370px;
  width: 600px;
  background: #fff;
  margin: auto;
  visibility: hidden;
  opacity: 0;
  transform: scale(0.5);
  transition: opacity 0.4s ease-in-out, visibility 0.4s ease-in-out, transform 0.4s ease-in-out;
}

.modal_header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 5px 10px;
  border-bottom: 1px solid #eee;
}

.modal_close {
  padding: 5px;
  cursor: pointer;
}

.modal_body {
  padding: 10px;
  text-align: justify;
}

</style>
