<template>
  <div id="content" class="container-fluid m-0 p-0 col-sm-md-lg-xl">
    <div id="header" class="pos-f-t">
        <nav id="" class="navbar navbar-expand">
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarToggleExternalContent" aria-controls="navbarToggleExternalContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <a class="navbar-brand">
                <img src="@/assets/logom7.png" />
            </a>
            <div id="navbarText" class="collapse navbar-collapse">
                <ul class="navbar-nav mr-auto">
                    <li class="nav-item active">
                        <a class="nav-link" href="#homepage">Inicio
                            <span class="sr-only">(current)</span>
                        </a>
                    </li>
                    <li  class="nav-item active">
                        <a class="nav-link" href="#who_are_we_looking_for">
                            ¿A quién buscamos?
                        </a>
                    </li>
                    <li class="nav-item active">
                        <a class="nav-link" href="#benefits">
                            Beneficios
                        </a>
                    </li>
                    <li class="nav-item active">
                        <a class="nav-link" href="#important_dates">
                            Fechas importantes
                        </a>
                    </li>
                    <li class="nav-item active">
                        <a class="nav-link" href="">
                            Jurado
                        </a>
                    </li>
                    <li class="nav-item active">
                        <a class="nav-link" href="">
                            Sobre nosotros
                        </a>
                    </li>
                    <li class="nav-item active">
                        <a class="nav-link" href="">
                            Aliados
                        </a>
                    </li>
                </ul>
                <span class="navbar-text">
                    <form>
                        <a href="">Contacto</a>
                    </form>
                </span>
            </div>
        </nav>
    </div>
    <div id="homepage" class="">
        <section>
            <div id="about" class="container-fluid bg-warning p-4">
                <div>
                    <p>¿Tienes una magnífica StartUp?</p>
                    <h1><strong>Haz parte de los 7 magníficos</strong></h1>
                    <p> "Inscríbete antes del "<strong>09 de julio de 2021.</strong></p>
                    <button @click="openModal()">Regístrate</button>
                </div>
            </div>
        </section>
        <section id="welcome">
            <div>
                <div>
                    <h2><strong>Bienvenidos a M7</strong></h2>
                </div>
                <div>
                    <p><strong>Más conocidos como "The Magnificient7" o el maravilloso western de la innovación y la creatividad, el primer Campus para 7 increíbles talentos.</strong></p>
                    <p>En el Grupo DDB, uno de los líderes en comunicaciones de marketing en Colombia, queremos reunir a 7 magníficas StartUps y crear un ecosistema único de trabajo, creciendo juntos durante al menos un año.</p>
                </div>
                <div>
                    <div>
                        <div>
                            <div>
                                <a href="">"Ver más"</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <div>
            <section id="who_are_we_looking_for">
                <div>
                    <div>
                        <div>
                            <div>
                                <div id="looking">
                                    <p>START UPS</p>
                                    <h2><strong>¿A quién buscamos?</strong></h2>
                                </div>
                                <div>
                                    <p>Las mejores StartUps de creatividad, contenido, data, marketing digital o relacionadas a las siguientes tecnologías, pueden participar.</p>
                                </div>
                            </div>
                            <div>
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
            <section id="benefits">
                <div>
                    <p>Beneficios</p>
                    <h2><strong>¿Qué obtienen las StartUps?</strong></h2>
                </div>
                <div>
                    <div>
                        <div>
                            <img src="https://m7innovationcenter.com/resources/dist/img/icon-beneficios-1.svg">
                            <p><strong>Acuerdo de alianza estratégica</strong> no vinculante con DDB</p>
                        </div>
                        <div>
                            <img src="https://m7innovationcenter.com/resources/dist/img/icon-beneficios-2.svg">
                            <p><strong>Espacios de trabajo exclusivos</strong> en los campos de Bogotá y Medellín</p>
                        </div>
                        <div>
                            <img src="https://m7innovationcenter.com/resources/dist/img/icon-beneficios-3.svg">
                            <p><strong>Acceso a créditos especiales</strong> de Amazon Cloud computing services</p>
                        </div>
                        <div>
                            <img src="https://m7innovationcenter.com/resources/dist/img/icon-beneficios-4.svg">
                            <p><strong>Eventos, capacitaciones,</strong> charlas y actividades, dentro del Campus.</p>
                        </div>
                        <div>
                        </div>
                    </div>
                    <div></div>
                </div>
            </section>
        </div>
        <div>
            <section id="important_dates">
                <div>
                    <div>
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
  -webkit-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
}

.navbar {
  position: relative;
  display: flex;
  align-items: center;
  padding: 0.5rem 1rem;
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
