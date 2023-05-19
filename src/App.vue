<script>
import  HeaderComponent  from "./components/HeaderComponent.vue";
import  FooterComponent  from "./components/FooterComponent.vue";
import  CodeDive  from "./components/CodeDive.vue";

  export default {
    name: 'App',
     components: {
      FooterComponent,
      HeaderComponent,
      CodeDive
     }  
  }

</script>

<template>
  <div>
    <header-component/>
    <main>
      <section class="py-1 text-center container">
        <div class="row py-lg-5">
          <div class="col-lg-9 col-md-8 mx-auto">
            <br />
            <CodeDive /><br /><br />
            <h1 class="fw-light text-success">CURSO FRONT END WEB DEVELOPER</h1>
            <p class="lead text-muted">
              Aquí encontrarás la recopilación de los ejercicios de evaluación
              del CURSO FRONT-END WEB DEVELOPER en modalidad teleformación de
              Multimedia Tarragona.
            </p>
            <p>Recuerda seguir las directrices de los enunciadios del curso</p>
          </div>
        </div>
      </section>
      <div class="album py-5 bg-light">
        <div class="container">
          <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 g-3">
            <div class="col">
              <div
                id="tarjeta"
                class="card shadow mb-3 text-light bg-dark px-2 pt-2"
              >
                <img id="tarjeta" src="./assets/E1.jpg" alt="" srcset="" />
                <div class="card-body">
                  <p class="card-text">
                    MODULO 1 PC1<br /><br />Tu primer contacto, crear una
                    estructura básica de html segun el enunciado
                  </p>
                  <div
                    class="d-flex justify-content-between align-items-center"
                  >
                    <div class="btn-group">
                      <a
                        href="https://codepen.io/david-maza-borjabad/pen/gOzRLPZ"
                        ><button type="button" class="btn btn-sm btn-warning">
                          Editar
                        </button></a
                      >
                      <!-- <button onclick="" type="button" class="btn btn-sm btn-primary ml-2">Enunciado</button> -->
                    </div>
                    <small class="text-muted"> HTML ⭐</small>
                  </div>
                </div>
              </div>
            </div>
            <div class="col">
              <div
                id="tarjeta"
                class="card shadow text-light bg-dark px-2 pt-2"
              >
                <img id="tarjeta" src="./assets/p2-1.jpg" alt="" srcset="" />

                <div class="card-body">
                  <p class="card-text">
                    MODULO 1 PC2<br /><br />
                    Añade los estilos CSS al ejercicio anterior, con las
                    pautas del enunciado.
                  </p>
                  <div
                    class="d-flex justify-content-between align-items-center"
                  >
                    <div class="btn-group">
                      <a
                        href="https://codepen.io/david-maza-borjabad/pen/dyeROzj?editors=1100"
                        ><button type="button" class="btn btn-sm btn-warning">
                          Editar
                        </button></a
                      >
                      <!-- <button action="" type="button" class="btn btn-sm btn-primary ml-2">Enunciado</button> -->
                    </div>
                    <small class="text-muted">CSS ⭐</small>
                  </div>
                </div>
              </div>
            </div>
            <div class="col">
              <div
                id="tarjeta"
                class="card shadow text-light bg-dark px-2 pt-2"
              >
                <img id="tarjeta" src="./assets/pc3-1.jpg" alt="" srcset="" />
                <div class="card-body">
                  <p class="card-text">
                    MODULO 1 PC3<br /><br />
                    Replica la imagen de la muestra y haz que sea reponsive
                  </p>
                  <div
                    class="d-flex justify-content-between align-items-center"
                  >
                    <div class="btn-group">
                      <a
                        href="https://codepen.io/david-maza-borjabad/pen/vYjZydb"
                        ><button type="button" class="btn btn-sm btn-warning">
                          Editar
                        </button></a
                      >
                      <!-- <button action="" type="button" class="btn btn-sm btn-primary ml-2">Enunciado</button> -->
                    </div>
                    <small class="text-muted">CSS ⭐⭐</small>
                  </div>
                </div>
              </div>
            </div>

            <div class="col">
              <div
                id="tarjeta"
                class="card shadow mb-3 text-light bg-dark px-2 pt-2"
              >
                <img id="tarjeta" src="./assets/pc1-2.jpg" alt="" srcset="" />

                <div class="card-body">
                  <p class="card-text">
                    MODULO 2 PC1<br /><br />
                    Pregunta el año de nacimiento al usuario y dile que signo
                    del horóscopo chino es.
                  </p>
                  <div
                    class="d-flex justify-content-between align-items-center"
                  >
                    <div class="btn-group">
                      <a
                        href="https://codepen.io/david-maza-borjabad/pen/oNdwYMa?editors=0010"
                        ><button type="button" class="btn btn-sm btn-warning">
                          Editar
                        </button></a
                      >
                      <a
                        href="https://raw.githubusercontent.com/d-maza/PC3-3-VUE/main/src/assets/E21.png"
                        ><button
                          action=""
                          type="button"
                          class="btn btn-sm btn-success ml-2"
                        >
                          Enunciado
                        </button></a
                      >
                    </div>
                    <small class="text-muted">JavaScript ⭐⭐⭐</small>
                  </div>
                </div>
              </div>
            </div>
            <div class="col">
              <div
                id="tarjeta"
                class="card shadow text-light bg-dark px-2 pt-2"
              >
                <img id="tarjeta" src="./assets/p2-2.jpg" alt="" srcset="" />

                <div class="card-body">
                  <p class="card-text">
                    MODULO 2 PC2<br /><br />Haz que el usuario entre en bucle
                    haz cumplir las condicion.
                  </p>

                  <div
                    class="d-flex justify-content-between align-items-center"
                  >
                    <div class="btn-group">
                      <a
                        href="https://codepen.io/david-maza-borjabad/pen/eYrRgJM"
                        ><button type="button" class="btn btn-sm btn-warning">
                          Editar
                        </button></a
                      >
                      <a
                        href="https://raw.githubusercontent.com/d-maza/PC3-3-VUE/main/src/assets/E22.png"
                        ><button
                          action=""
                          type="button"
                          class="btn btn-sm btn-success ml-2"
                        >
                          Enunciado
                        </button></a
                      >
                    </div>
                    <small class="text-muted">JavaScript ⭐⭐</small>
                  </div>
                </div>
              </div>
            </div>
            <div class="col">
              <div
                id="tarjeta"
                class="card shadow text-light bg-dark px-2 pt-2"
              >
                <img id="tarjeta" src="./assets/pc3-2.jpg" alt="" srcset="" />

                <div class="card-body">
                  <p class="card-text">
                    MODULO 2 PC3<br /><br />Haz que según la respuesta del
                    usuario muestre por el DOM el resultado.
                  </p>
                  <div
                    class="d-flex justify-content-between align-items-center"
                  >
                    <div class="btn-group">
                      <!-- <a href="https://codepen.io/david-maza-borjabad/pen/ZEoyLJR"> <button type="button" class="btn btn-sm btn-warning">Editar</button></a> -->
                      <a
                        href="https://raw.githubusercontent.com/d-maza/PC3-3-VUE/main/src/assets/E23.png"
                        ><button
                          action=""
                          type="button"
                          class="btn btn-sm btn-success ml-2"
                        >
                          Enunciado
                        </button></a
                      >
                    </div>
                    <small class="text-muted">JavaScript ⭐⭐</small>
                  </div>
                </div>
              </div>
            </div>

            <div class="col">
              <div
                id="tarjeta"
                class="card shadow mb-3 text-light bg-dark px-2 pt-2"
              >
                <img id="tarjeta" src="./assets/pc1-3.jpg" alt="" srcset="" />

                <div class="card-body">
                  <p class="card-text">
                    MODULO 3 PC1<br /><br />Crea una Single-Page Application
                    (SPA) usando la CDN de VUE.
                  </p>
                  <div
                    class="d-flex justify-content-between align-items-center"
                  >
                    <div class="btn-group">
                      <a
                        href="https://raw.githubusercontent.com/d-maza/PC3-3-VUE/main/src/assets/E31.png"
                        ><button
                          action=""
                          type="button"
                          class="btn btn-sm btn-success ml-2"
                        >
                          Enunciado
                        </button></a
                      >
                    </div>
                    <small class="text-muted">VUE ⭐⭐⭐</small>
                  </div>
                </div>
              </div>
            </div>
            <div class="col">
              <div
                id="tarjeta"
                class="card shadow text-light bg-dark px-2 pt-2"
              >
                <img id="tarjeta" src="./assets/pc2-3.jpg" alt="" srcset="" />

                <div class="card-body">
                  <p class="card-text">
                    MODULO 3 PC2<br /><br />Crea un formulario en un HTML y
                    conecta con el JS con el (v-model)
                  </p>
                  <div
                    class="d-flex justify-content-between align-items-center"
                  >
                    <div class="btn-group">
                      <a
                        href="https://codepen.io/david-maza-borjabad/pen/PoeKdyE"
                      >
                        <button type="button" class="btn btn-sm btn-warning">
                          Editar
                        </button></a
                      >
                      <a
                        href="https://raw.githubusercontent.com/d-maza/PC3-3-VUE/main/src/assets/E32.PNG"
                        ><button
                          type="button"
                          class="btn btn-sm btn-success ml-2"
                        >
                          Enunciado
                        </button></a
                      >
                    </div>
                    <small class="text-muted">VUE ⭐⭐⭐</small>
                  </div>
                </div>
              </div>
            </div>
            <div class="col">
              <div
                id="tarjeta"
                class="card shadow text-light bg-dark px-2 pt-2"
              >
                <img id="tarjeta" src="./assets/pc3-3.jpg" alt="" srcset="" />

                <div class="card-body">
                  <p class="card-text">
                    MODULO 3 PC3<br /><br />Este es el ejercicio final de curso
                    y es lo que estás contemplando
                  </p>
                  <div
                    class="d-flex justify-content-between align-items-center"
                  >
                    <div class="btn-group">
                      <a
                        href="https://raw.githubusercontent.com/d-maza/PC3-3-VUE/main/src/assets/E33.png"
                        ><button
                          type="button"
                          class="btn btn-sm btn-success ml-2"
                        >
                          Enunciado
                        </button></a
                      >
                      <!-- <button type="button" class="btn btn-sm btn-outline-secondary">Edit</button> -->
                    </div>
                    <small class="text-muted">VUE ⭐⭐⭐⭐</small>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </main>

    <footer-component />
  </div>
</template>

<style>
.bd-placeholder-img {
  font-size: 1.125rem;
  text-anchor: middle;
  -webkit-user-select: none;
  -moz-user-select: none;
  user-select: none;
}

@media (min-width: 768px) {
  .bd-placeholder-img-lg {
    font-size: 3.5rem;
  }
}

.b-example-divider {
  height: 3rem;
  background-color: rgba(0, 0, 0, 0.1);
  border: solid rgba(0, 0, 0, 0.15);
  border-width: px 0;
  box-shadow: inset 0 0.5em 1.5em rgba(7, 7, 7, 0.1),
    inset 0 0.125em 0.5em rgba(0, 0, 0, 0.15);
}

.b-example-vr {
  flex-shrink: 0;
  width: 1.5rem;
  height: 100vh;
}

.bi {
  vertical-align: -0.125em;
  fill: currentColor;
}

.nav-scroller {
  position: relative;
  z-index: 2;
  height: 2.75rem;
  overflow-y: hidden;
}

.nav-scroller .nav {
  display: flex;
  flex-wrap: nowrap;
  padding-bottom: 1rem;
  margin-top: -1px;
  overflow-x: auto;
  text-align: center;
  white-space: nowrap;
  -webkit-overflow-scrolling: touch;
}

#tarjeta {
  border-radius: 5px;
}
</style>


