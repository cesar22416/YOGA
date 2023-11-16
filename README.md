<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-4bw+/aepP/YC94hEpVNVgiZdgIC5+VKNBQNGCHeKRQN+PtmoHDEXuppvnDJzQIu9" crossorigin="anonymous">
  <link rel="stylesheet" href="style.css">
  <script src="scrip.js"></script>

  <title>YOGA</title>
</head>

<body>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand titulo" href="#">YOGA</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup"
        aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <button type="button" class="home btn " data-bs-toggle="modal" data-bs-target="#ABOUT">RUTINAS</button>
          <button type="button" class="home btn " data-bs-toggle="modal" data-bs-target="#WORK">TALLERES</button>
          <button type="button" class="home btn " data-bs-toggle="modal" data-bs-target="#CONTACT">GALERIA</button>
          <button type="button" class="home btn " data-bs-toggle="modal" data-bs-target="#CONTACTO">CONTACTO</button>
        </div>
      </div>
    </div>
  </nav>

  <article class="container-fluid  art " style="width: 100%;">
    <div class="row d-flex justify-content-center align-items-center">
      <div class="caja col-6 card ">
        <h2 class="meditar">
          MEDITA - CRECE - SUEÑA
        </h2>
        <h4 class="siete ">SIETE CHAKRAS + VIDA</h4>
        <p class="parra">El yoga es una práctica que conecta el cuerpo y la mente. </p>
      </div>
      <div class="col-6 ">
        <img src="img/logo.png" alt="logo" class="d-flex justify-content-center" style="width: 100%;">
      </div>
    </div>
  </article>


  <div class="modal fade" id="CONTACTO" tabindex="-1" aria-labelledby="CONTACTOLabel" aria-hidden="true">
    <div class="modal-dialog modal-xl">
      <div class="modal-content  d-flex justify-content-center">
        <div class="modal-header">
          <h5 class="modal-title" id="CONTACTOLabel">CONTACTO</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          <section class="get-in-touch">
            <form class="contact-form row">
              <div class="form-field col x-50">
                <input id="name" class="input-text js-input" type="text" required>
                <label class="label" for="name">Name</label>
              </div>
              <div class="form-field col x-50">
                <input id="email" class="input-text js-input" type="email" required>
                <label class="label" for="email">E-mail</label>
              </div>
              <div class="form-field col x-100">
                <input id="message" class="input-text js-input" type="text" required>
                <label class="label" for="message">Message</label>
              </div>
              <div class="form-field col x-100 align-center">
                <input class="submit-btn" type="submit" value="Submit">
              </div>
            </form>
          </section>
          <p class="note">Based on <a class="link" href="http://redcollar.digital/contacts/" target="blank">Red Collar
              Contact
              Form</a>.</p>
        </div>
      </div>
    </div>
  </div>



  <div class="modal fade" id="ABOUT" tabindex="-1" aria-labelledby="ABOUTLabel" aria-hidden="true">
    <div class="modal-dialog modal-xl">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="ABOUTLabel">RUTINAS</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          <div class="row row-cols-1 row-cols-md-2 g-4">
            <div class="col">
              <div class="card">
                <img
                  src="https://hips.hearstapps.com/hmg-prod/images/postura-montana-1543322841.gif?crop=1xw:1xh;center,top&resize=980:*"
                  class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Postura de la montaña</h5>
                  <p class="card-text">Cómo hacerla: erguida y con los pies ligeramente separados, desciende los brazos
                    a cada lado con las palmas hacia delante. Separa los dedos de los pies, levanta el pecho y baja los
                    omóplatos.<br>

                  <p class="fw-bold card-text">Beneficios:</p>
                  <p class="card-text">conectamos con nuestro cuerpo para comenzar la sesión.</p>
                </div>
              </div>
            </div>

            <div class="col">
              <div class="card">
                <img
                  src="https://hips.hearstapps.com/hmg-prod/images/postura-silla-1543322952.gif?crop=1xw:1xh;center,top&resize=980:*"
                  class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Postura de la silla</h5>
                  <p class="card-text">Cómo hacerla: levanta los brazos por encima de la cabeza con las palmas hacia
                    dentro. Dobla las rodillas y agáchate como si fueras a sentarte en una silla.<br>
                  <p class="fw-bold card-text">Beneficios:</p>
                  <p class="card-text"> ayuda a mejorar nuestro equilibrio mientras fortalecemos piernas.</p>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card">
                <img
                  src="https://hips.hearstapps.com/hmg-prod/images/postura-uttanasana-1543322956.gif?crop=1xw:1xh;center,top&resize=980:*"
                  class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Uttanasana</h5>
                  <p class="card-text">Cómo hacerla: con las piernas rectas y el pecho levantado, inclínate hacia
                    delante hasta tocar el suelo manteniendo el abdomen tenso y la espalda recta. Si no eres capaz de
                    llegar, no te preocupes, intenta llegar a las espinillas<br>

                  <p class="fw-bold card-text">Beneficios:</p>
                  <p class="card-text"> Estiramos toda la parte inferior de la espalda y cadena posterior de las
                    piernas.</p>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card">
                <img
                  src="https://hips.hearstapps.com/hmg-prod/images/postura-low-lunge-1543322954.gif?crop=1xw:1xh;center,top&resize=980:*"
                  class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Low Lunge</h5>
                  <p class="card-text">Cómo hacerla: apoya los pies y las manos en el suelo y extiende el pie derecho
                    hacia atrás mientras doblas la rodilla izquierda en 90°.

                    Estas cuatro posturas de yoga para principiantes que llevamos hasta ahora, forman parte del saludo
                    al sol, un movimiento esencial.<br>

                  <p class="fw-bold card-text">Beneficios:</p>
                  <p class="card-text"> Con este ejercicio abrimos espalda alta y estiramos cadera.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        F
      </div>
    </div>
  </div>


  <div class="modal fade" id="WORK" tabindex="-1" aria-labelledby="WORKLabel" aria-hidden="true">
    <div class="modal-dialog modal-xl">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="WORKLabel">Talleres</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>


        <div class="modal-body">
          <div class="card mb-3">
            <img src="https://www.clasesdeyogaonline.com/wp-content/uploads/2022/09/CYO-TALLERES-LANDING-MUJERES_50.jpg"
              class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">TALLER DE YOGA PARA MUJERES 50+</h5>
              <p class="card-text">El Ciclo Yoga para Mujeres 50+ tiene como objetivo contribuir a crear bienestar y
                salud en la mujer, respetando los
                cambios que ocurren en el organismo y tratando de sacar lo mejor que lleva dentro cada mujer. Los 3
                objetivos del Ciclo
                Online de Yoga para mujeres 50+ se pueden resumir en: mejorar la salud, conseguir un bienestar integral,
                y fortalecer la
                musculatura.
              </p>
              <p class="card-text"><small class="text-muted">informacion</small></p>
              <button type="button" class="btn btn-outline-info">inscripcion</button>
            </div>
            <div class="card mb-3">
              <img
                src="https://www.clasesdeyogaonline.com/wp-content/uploads/2022/08/Taller-princpiantes-youtube-01.jpg"
                class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title">Taller de Yoga para Principiantes</h5>
                <p class="card-text">Lo que más valoran nuestros alumnos es la libertad de horarios. Poder hacer Yoga en
                  cualquier momento y desde cualquier
                  lugar es fundamental para ellos.</p>
                <p class="card-text"><small class="text-muted">informacion</small></p>
                <button type="button" class="btn btn-outline-info">inscripcion</button>
              </div>
            </div>
            <div class="card mb-3">
              <img
                src="https://www.clasesdeyogaonline.com/wp-content/uploads/2022/09/CYO-LANDING-TALLER-ANTAR-MOUNA.jpg"
                class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title">TALLER DE MEDITACIÓN ANTAR MOUNA</h5>
                <p class="card-text">Antar Mouna (Antar = Interior, Mouna = Silencio) es una práctica de meditación que
                  tiene como objetivo la escucha
                  interior. Es un proceso a través del cual se desarrolla la comprensión de la propia mente y su
                  funcionamiento en
                  relación al mundo abriendo los canales sensoriales de fuera a dentro y de fuera hacia dentro. Es en si
                  misma una
                  práctica que propone un proceso en varias fases para llegar al estado de integración del si mismo.
                </p>
                <p class="card-text"><small class="text-muted">informacion</small></p>
                <button type="button" class="btn btn-outline-info">inscripcion</button>
              </div>
            </div>


          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="modal fade" id="CONTACT" tabindex="-1" aria-labelledby="CONTACTLabel" aria-hidden="true">
    <div class="modal-dialog modal-xl">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="CONTACTLabel">GALERIA</h5>
          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
        </div>
        <div class="modal-body">
          <div id="carouselExampleDark" class="carousel carousel-dark slide" data-bs-ride="carousel">
            <div class="carousel-indicators">
              <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active"
                aria-current="true" aria-label="Slide 1"></button>
              <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1"
                aria-label="Slide 2"></button>
              <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2"
                aria-label="Slide 3"></button>
            </div>
            <div class="carousel-inner">
              <div class="carousel-item active" data-bs-interval="10000">
                <img
                  src="https://images.pexels.com/photos/3150250/pexels-photo-3150250.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
                  class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                  <h5>First slide label</h5>
                  <p>Some representative placeholder content for the first slide.</p>
                </div>
              </div>
              <div class="carousel-item" data-bs-interval="2000">
                <img
                  src="https://images.pexels.com/photos/3658399/pexels-photo-3658399.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
                  class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                  <h5>Second slide label</h5>
                  <p>Some representative placeholder content for the second slide.</p>
                </div>
              </div>
              <div class="carousel-item">
                <img
                  src="https://images.pexels.com/photos/3820393/pexels-photo-3820393.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
                  class="d-block w-100" alt="...">
                <div class="carousel-caption d-none d-md-block">
                  <h5>Third slide label</h5>
                  <p>Some representative placeholder content for the third slide.</p>
                </div>
              </div>
            </div>
            <div class="carousel-item">
              <img
                src="https://images.pexels.com/photos/4057840/pexels-photo-4057840.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
                class="d-block w-100" alt="...">
              <div class="carousel-caption d-none d-md-block">
                <h5>Third slide label</h5>
                <p>Some representative placeholder content for the third slide.</p>
              </div>
            </div>
          </div>


          <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark"
            data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark"
            data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
          </button>
        </div>

      </div>
    </div>
  </div>
  </div>


  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-HwwvtgBNo3bZJJLYd8oVXjrBZt8cqVSpeBNS5n7C8IVInixGAoxmnlMuBnhbgrkm"
    crossorigin="anonymous"></script>


  <footer class="footer-distributed" style="height: 70px;">
    <p class="footer-links">

      <a class="link-1" href="#"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
          class="bi bi-facebook" viewBox="0 0 16 16">
          <path
            d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951z" />
        </svg></a>

      <a href="#"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
          class="bi bi-instagram" viewBox="0 0 16 16">
          <path
            d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.917 3.917 0 0 0-1.417.923A3.927 3.927 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.916 3.916 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.926 3.926 0 0 0-.923-1.417A3.911 3.911 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0h.003zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599.28.28.453.546.598.92.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.47 2.47 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.478 2.478 0 0 1-.92-.598 2.48 2.48 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233 0-2.136.008-2.388.046-3.231.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92.28-.28.546-.453.92-.598.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045v.002zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92zm-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217zm0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334z" />
        </svg></a>

      <a href="#"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
          class="bi bi-youtube" viewBox="0 0 16 16">
          <path
            d="M8.051 1.999h.089c.822.003 4.987.033 6.11.335a2.01 2.01 0 0 1 1.415 1.42c.101.38.172.883.22 1.402l.01.104.022.26.008.104c.065.914.073 1.77.074 1.957v.075c-.001.194-.01 1.108-.082 2.06l-.008.105-.009.104c-.05.572-.124 1.14-.235 1.558a2.007 2.007 0 0 1-1.415 1.42c-1.16.312-5.569.334-6.18.335h-.142c-.309 0-1.587-.006-2.927-.052l-.17-.006-.087-.004-.171-.007-.171-.007c-1.11-.049-2.167-.128-2.654-.26a2.007 2.007 0 0 1-1.415-1.419c-.111-.417-.185-.986-.235-1.558L.09 9.82l-.008-.104A31.4 31.4 0 0 1 0 7.68v-.123c.002-.215.01-.958.064-1.778l.007-.103.003-.052.008-.104.022-.26.01-.104c.048-.519.119-1.023.22-1.402a2.007 2.007 0 0 1 1.415-1.42c.487-.13 1.544-.21 2.654-.26l.17-.007.172-.006.086-.003.171-.007A99.788 99.788 0 0 1 7.858 2h.193zM6.4 5.209v4.818l4.157-2.408L6.4 5.209z" />
        </svg></a>

      <a href="#"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
          class="bi bi-whatsapp" viewBox="0 0 16 16">
          <path
            d="M13.601 2.326A7.854 7.854 0 0 0 7.994 0C3.627 0 .068 3.558.064 7.926c0 1.399.366 2.76 1.057 3.965L0 16l4.204-1.102a7.933 7.933 0 0 0 3.79.965h.004c4.368 0 7.926-3.558 7.93-7.93A7.898 7.898 0 0 0 13.6 2.326zM7.994 14.521a6.573 6.573 0 0 1-3.356-.92l-.24-.144-2.494.654.666-2.433-.156-.251a6.56 6.56 0 0 1-1.007-3.505c0-3.626 2.957-6.584 6.591-6.584a6.56 6.56 0 0 1 4.66 1.931 6.557 6.557 0 0 1 1.928 4.66c-.004 3.639-2.961 6.592-6.592 6.592zm3.615-4.934c-.197-.099-1.17-.578-1.353-.646-.182-.065-.315-.099-.445.099-.133.197-.513.646-.627.775-.114.133-.232.148-.43.05-.197-.1-.836-.308-1.592-.985-.59-.525-.985-1.175-1.103-1.372-.114-.198-.011-.304.088-.403.087-.088.197-.232.296-.346.1-.114.133-.198.198-.33.065-.134.034-.248-.015-.347-.05-.099-.445-1.076-.612-1.47-.16-.389-.323-.335-.445-.34-.114-.007-.247-.007-.38-.007a.729.729 0 0 0-.529.247c-.182.198-.691.677-.691 1.654 0 .977.71 1.916.81 2.049.098.133 1.394 2.132 3.383 2.992.47.205.84.326 1.129.418.475.152.904.129 1.246.08.38-.058 1.171-.48 1.338-.943.164-.464.164-.86.114-.943-.049-.084-.182-.133-.38-.232z" />
        </svg></a>

      <a href="#"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
          class="bi bi-envelope" viewBox="0 0 16 16">
          <path
            d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V4Zm2-1a1 1 0 0 0-1 1v.217l7 4.2 7-4.2V4a1 1 0 0 0-1-1H2Zm13 2.383-4.708 2.825L15 11.105V5.383Zm-.034 6.876-5.64-3.471L8 9.583l-1.326-.795-5.64 3.47A1 1 0 0 0 2 13h12a1 1 0 0 0 .966-.741ZM1 11.105l4.708-2.897L1 5.383v5.722Z" />
        </svg></a>

      <a href="#"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
          class="bi bi-geo-alt" viewBox="0 0 16 16">
          <path
            d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A31.493 31.493 0 0 1 8 14.58a31.481 31.481 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94zM8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10z" />
          <path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4zm0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6z" />
        </svg></a>
    <p>Cesar Montilla Proyecto educativo &copy; 2015</p>

    </p>
  </footer>
</body>

</html>
