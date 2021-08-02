<template>
  <div id="content" class="container-fluid m-0 p-0 col-sm-md-lg-xl">
    <div id="header" class=" header_nav" @scroll="scrollMenu()">
        <nav id="mev" class="navbar navbar-expand">
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarToggleExternalContent" aria-controls="navbarToggleExternalContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <a class="navbar-brand">
                <img src="@/assets/logom7white.png" />
            </a>
            <div id="navbarText" class="collapse navbar-collapse">
                <ul class="nav nav-fill">
                    <li class="nav-item active">
                        <a class=" nav-link active" href="#homepage">Inicio
                            <span class="sr-only"></span>
                        </a>
                    </li>
                    <li  class="nav-item">
                        <a class="nav-link" href="#who_are_we_looking_for">
                            ¿A quién buscamos?
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#benefits">
                            Beneficios
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#important_dates">
                            Fechas importantes
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="">
                            Jurado
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="">
                            Sobre nosotros
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="">
                            Aliados
                        </a>
                    </li>
                </ul>
                <span class="navbar-text">
                    <form class="form-inline my-2 my-lg-0">
                        <button class="btn  btn btn-sm btn-outline-secondary btn-outline-dark my-2 my-sm-0" type="submit">
                            <a href="#contact" class="nav-link"><strong>Contacto</strong></a>
                        </button>
                    </form>
                </span>
            </div>
        </nav>
    </div>
    <div id="homepage" class="">
        <section>
            <div id="about" class="container-fluid bg-warning p-4 image align-items-end justify-content-end d-flex">
                <div class="text1">
                    <p id="p_about">¿Tienes una magnífica StartUp?</p>
                    <h1><strong>Haz parte de los 7 magníficos</strong></h1>
                    <p> Inscríbete antes del <strong>09 de julio de 2021.</strong></p>
                    <button id="registration" class="btn btn-dark mt-4 next-step" @click="openModal()">Regístrate</button>
                </div>
            </div>
        </section>
        <section id="welcome">
            <div class="container pad">
                <div class="welcomem7">
                    <h2><strong>Bienvenidos a M7</strong></h2>
                </div>
                <div class="text2">
                    <p><strong>Más conocidos como "The Magnificient7" o el maravilloso western de la innovación y la creatividad, el primer Campus para 7 increíbles talentos.</strong></p>
                    <p>En el Grupo DDB, uno de los líderes en comunicaciones de marketing en Colombia, queremos reunir a 7 magníficas StartUps y crear un ecosistema único de trabajo, creciendo juntos durante al menos un año.</p>
                </div>
                <div>
                    <div>
                        <div class="col-md-7 mx-auto">
                            <div class="">
                                <h4 class="more">
                                    <a href="">Ver más</a>
                                </h4>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <div>
            <section class="pad1 search d-flex align-items-center" id="who_are_we_looking_for">
                <div class="container-fluid">
                    <div class="who_looking">
                        <div class="row d-flex align-items-center">
                            <div class="col-md-6 text_col1">
                                <div class="title text3" id="looking">
                                    <p>START UPS</p>
                                    <h2><strong>¿A quién buscamos?</strong></h2>
                                </div>
                                <div class="subtitle text3 pad3">
                                    <p>Las mejores StartUps de creatividad, contenido, data, marketing digital o relacionadas a las siguientes tecnologías, pueden participar.</p>
                                </div>
                            </div>
                            <div class="col-md-6 mb-3">
                                <ul>
                                    <li>
                                        <span>01.</span>
                                        <p>AI / VR / AR</p>
                                    </li>
                                    <li>
                                        <span>02.</span>
                                        <p>ALGORITHMS</p>
                                    </li>
                                    <li>
                                        <span>03.</span>
                                        <p>MACHINE LEARNING</p>
                                    </li>
                                    <li>
                                        <span>04.</span>
                                        <p>MARKETING AUTOMATION</p>
                                    </li>
                                    <li>
                                        <span>05.</span>
                                        <p>TECNOLOGÍAS PERIFÉRICAS</p>
                                    </li>
                                    <li>
                                        <span>06.</span>
                                        <p>AUTOMATIZACIÓN DE PROCESOS Y DE CONTENIDOS</p>
                                    </li>
                                    <li>
                                        <span>07.</span>
                                        <p>PREDICTIVOS DE COMPORTAMIENTOS</p>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </div>
        <div>
            <section class="bg-lite-gray py-5" id="benefits">
                <div class="container">
                    <div class="title text3">
                        <p>Beneficios</p>
                        <h2><strong>¿Qué obtienen las StartUps?</strong></h2>
                    </div>
                    <div class="startups py-4">
                    <div class="row text3 features">
                        <div class="col-md-3 mb-4">
                            <img src="https://m7innovationcenter.com/resources/dist/img/icon-beneficios-1.svg">
                            <p><strong>Acuerdo de alianza estratégica</strong> no vinculante con DDB</p>
                        </div>
                        <div class="col-md-3 mb-4">
                            <img src="https://m7innovationcenter.com/resources/dist/img/icon-beneficios-2.svg">
                            <p><strong>Espacios de trabajo exclusivos</strong> en los campos de Bogotá y Medellín</p>
                        </div>
                        <div class="col-md-3 mb-4">
                            <img src="https://m7innovationcenter.com/resources/dist/img/icon-beneficios-3.svg">
                            <p><strong>Acceso a créditos especiales</strong> de Amazon Cloud computing services</p>
                        </div>
                        <div class="col-md-3 mb-4">
                            <img src="https://m7innovationcenter.com/resources/dist/img/icon-beneficios-4.svg">
                            <p><strong>Eventos, capacitaciones,</strong> charlas y actividades, dentro del Campus.</p>
                        </div>
                        <div>
                        </div>
                    </div>
                    <div></div>
                </div>
                </div>
            </section>
        </div>
        <div>
            <section class="my-5 dates" id="important_dates">
                <div class="container">
                    <div class="title text3">
                        <p>FECHAS IMPORTANTES</p>
                        <h2><strong>¿Hasta cuándo participar?</strong></h2>
                    </div>
                    <div>
                        <p>La convocatoria durará 8 días, agrega un recordatorio a tu calendario para participar.</p>
                    </div>
                    <div>
                        <div>
                            <div class="calendar">
                                <div class="month">
                                    <strong><a href="">  </a>AGOSTO</strong>
                                </div>
                            </div>
                        </div>
                        <div>
                            <div class="cal_week">
                                <div>DOM</div>
                                <div>LUN</div>
                                <div>MAR</div>
                                <div>MIE</div>
                                <div>JUE</div>
                                <div>VIE</div>
                                <div>SAB</div>
                            </div>
                            <div class="cal_days">
                                <div>
                                    <span>1</span>
                                </div>
                                <div>
                                    <span>2</span>
                                </div>
                                <div>
                                    <span>3</span>
                                </div>
                                <div>
                                    <span>4</span>
                                </div>
                                <div>
                                    <span>5</span>
                                </div>
                                <div>
                                    <span>6</span>
                                </div>
                                <div>
                                    <span>7</span>
                                </div>
                                <div>
                                    <span>8</span>
                                </div>
                                <div>
                                    <span>9</span>
                                </div>
                                <div>
                                    <span>10</span>
                                </div>
                                <div>
                                    <span>11</span>
                                </div>
                                <div>
                                    <span>12</span>
                                </div>
                                <div>
                                    <span>13</span>
                                </div>
                                <div>
                                    <span>14</span>
                                </div>
                                <div>
                                    <span>15</span>
                                </div>
                                <div>
                                    <span>16</span>
                                </div>
                                <div>
                                    <span>17</span>
                                </div>
                                <div>
                                    <span>18</span>
                                </div>
                                <div>
                                    <span>19</span>
                                </div>
                                <div>
                                    <span>20</span>
                                </div>
                                <div>
                                    <span>21</span>
                                </div>
                                <div>
                                    <span>22</span>
                                </div>
                                <div>
                                    <span>23</span>
                                </div>
                                <div>
                                    <span>24</span>
                                </div>
                                <div>
                                    <span>25</span>
                                </div>
                                <div>
                                    <span>26</span>
                                </div>
                                <div>
                                    <span>27</span>
                                </div>
                                <div>
                                    <span>28</span>
                                </div>
                                <div>
                                    <span>29</span>
                                </div>
                                <div>
                                    <span>30</span>
                                </div>
                                <div>
                                    <span>31</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
        </div>
        <div id="contact" class="container">
        </div>
        <div id="footer" class="container">
        </div>
        </div>
  </div>
</template>

<script>

import Modal from './Modal.vue'

export default {
  name: 'HomePage',
  components: {
    Modal
  },
  methods: {
    openModal () {
      const modal = document.getElementById('modal')
      modal.classList.add('show')
    },

    scrollMenu () {
      var header = document.getElementById('header')

      window.onscroll = function () {
        if (window.pageYOffset > 50) {
          header.style.backgroundColor = '#161616'
        } else {
          header.style.backgroundColor = 'transparent'
        }
      }
    },

    scrollNav () {
      var menu = document.getElementById('menu') // Identify target

      window.addEventListener('scroll', function (event) { // To listen for event
        event.preventDefault()

        if (window.scrollY > 50) {
          menu.style.backgroundColor = '#161616' // or default color
        } else {
          menu.style.backgroundColor = 'transparent'
        }
      })
    }
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

#header {
  position: fixed;
  width: 100%;
  padding: 1rem;
  z-index: 99;
  transition: all 0.2s ease-in-out;
}

#header .header_nav {
    padding: 0 1rem!important;
}

.navbar {
  position: relative;
  display: flex;
  align-items: center;
  padding: 0.5rem 1rem;
}

#mev img {
    width: 109px;
    height: 57px;
}

nav a {
    color: #fff;
}

nav a:hover {
    color: #fff;
    text-decoration: underline;
}

nav form button a {
    color: #161616;
}

#homepage .image {
    height: 100vh;
    width: 100%;
}

#homepage .image p {
    max-width: 400px;
    margin: 0 0 0 auto;
    font-size: 1.38rem;
}

#homepage .image h1 {
    font-size: 3rem;
    line-height: 60px;
    text-transform: uppercase;
}

h4 {
    font-size: 1.5rem;
}

p {
    margin-top: 0;
    margin-bottom: 1rem;
}
strong {
    font-weight: 700!important;
}

#about {
    background: url("https://m7innovationcenter.com/resources/dist/img/banner-desktop.jpg") 0% 0% / cover no-repeat;
    visibility: visible;
}

#about #registration {
    font-size: 1.38rem;
    cursor: pointer;
}

#about #registration:hover {
    border-color: #161616;
    background-color: #fff;
    color: #161616;
}

.text1 {
    max-width: 450px;
    margin: 3rem;
    text-align: right;
    float: right;
}

.text1 #p_about {
    text-transform: uppercase;
}

.align-items-end {
    align-items: flex-end!important;
}

.align-items-center {
    align-items: center!important;
}

.justify-content-end {
    justify-content: flex-end!important;
}

.d-flex {
    display: flex!important;;
}

#welcome .pad {
    padding-bottom: 3rem!important;
    padding-top: 3rem!important;
}

#welcome .welcomem7 {
    text-transform: uppercase!important;;
    text-align: center!important;;
    margin-bottom: 3rem!important;
    margin-top: 3rem!important;
}

.welcomem7 h2 {
    font-size: 2.5rem;
}

#welcome .text2 {
    max-width: 600px;
    margin: 0 auto;
    text-align: center!important;
}

.more {
    display: inline-block;
}

.more a {
    color: #161616;
    text-decoration: underline;
    font-size: 1rem;
}

#homepage .search {
    background: url(https://m7innovationcenter.com/resources/dist/img/bg-a-quien-buscamos.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    width: 100%;
    height: 90vh;
}

#who_are_looking_for .pad1 {
    padding-bottom: 3rem!important;
    padding-top: 3rem!important;
}

.row {
    flex-wrap: wrap;
    margin-right: -15px;
    margin-left: -15px;
}

.text_col1 {
    text-align: right!important;
}

#homepage .title {
    padding: 4rem 0 0;
}

.text3 {
    text-align: center!important;
}

#homepage .title p {
    background: #fdd200;
    display: table;
    margin: 0 auto;
    letter-spacing: 5px;
    font-size: 0.9rem;
    padding: 0 1px 0 5px;
    color: #141414;
    text-transform: uppercase;
}

#homepage .title h2 {
    font-size: 2.5rem;
    color: #fdd200;
}

#homepage .subtitle {
    max-width: 430px;
    margin: 0 auto;
    font-size: 0.9rem;
}

.pad3 {
    padding-bottom: 3rem!important;
}

#homepage .search .subtitle p {
    max-width: 300px;
    margin: 0 auto;
}

#homepage .who_looking .subtitle p {
    color: #fff;
}

ul {
    margin-top: 0;
    margin-bottom: 1rem;
}

li {
    text-align: left;
}

#homepage .who_looking li {
    color: #fff;
    list-style: none;
}

#homepage .who_looking li span {
    color: #fdd200;
    display: inline-block;
    padding-right: 1rem;
    padding-bottom: 1rem;
    width: 30px;
}

#homepage .who_looking li p {
    margin-left: 1rem;
    margin: 0;
    display: inline-block;
    border-left: 1px solid #fdd200;
    padding-left: 1rem;
    padding-bottom: 1.6rem;
}

#homepage #benefits h2 {
    color: #141414;
}

#homepage .startups img {
    width: 50%!important;
}

#homepage img {
    object-fit: cover;
    object-position: center;
}

img {
    vertical-align: middle;
    border-style: none;
}

#homepage .startups p {
    max-width: 195px;
    margin: 0 auto;
    padding-top: 1rem;
}

#homepage .dates {
    overflow: hidden;
}

#homepage .dates h2 {
    color: #141414;
}

.cal_week {
    background-color: #fff;
    display: grid;
    grid-template-columns: repeat(7,1fr);
}

.cal_days {
    display: grid;
    grid-template-columns: repeat(7,1fr);
}

</style>
