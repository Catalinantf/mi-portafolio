<template>
  <div class="home">
    <b-container>
      <b-card-group class="mb-4">
        <!-- card academia -->
        <b-card bg-variant="transparent" border-variant="light">
          <a href="https://academia-ventas.web.app/home" target="_blank">
            <img
              class="card-img-top"
              src="../assets/academiaventas.jpg"
              alt="Card image cap"
            />
          </a>

          <b-card-text>
            <h4>Academia de Ventas</h4>
            <small class="muted">
              Proyecto final del Bootcamp de Front End dev in Vue.JS. Es un
              sitio web responsivo que sirve para dar a conocer la academia y
              también al iniciar sesión el administrador puede gestionar
              interesados, alumnos, cursos, cupos etc.
            </small>
          </b-card-text>
          <template #footer>
            Para este proyeco utilicé Firebase, Vue, BootstrapVue y Vuetify.
                            <br>
            <button type="button" class="btn btn-outline-secondary">
              <a
                href="https://github.com/Catalinantf/academia-ventas"
                >Repositorio</a
              >
            </button>
          </template>
        </b-card>
        <!-- card gigeo -->
        <b-card bg-variant="transparent" border-variant="light">
          <a href="https://catalinantf.github.io/gigeo/" target="_blank">
            <img
              class="card-img-top"
              src="../assets/gigeo-img.png"
              alt="Card image cap"
            />
          </a>
          <b-card-text>
            <h4>Gigeo</h4>
            <small class="muted">
              Ejercicio para Bootcamp de Front End dev in Vue.JS. Es un sitio
              web responsivo que busca presentar el trabajo de una artista
              musical.
            </small>
          </b-card-text>
          <template #footer>
            Para este ejercicio utilicé HTML, Saas y Bootstrap
            <br>
                            <br>
            <button type="button" class="btn btn-outline-secondary">
              <a
                href="https://github.com/Catalinantfgigeo/"
                >Repositorio</a
              >
            </button>
          </template>
        </b-card>
        <!-- card Animales -->
        <b-card bg-variant="transparent" border-variant="light">
          <a
            href="https://nostalgic-volhard-88f2d2.netlify.app/"
            target="_blank"
          >
            <img
              src="../assets/animales-salvajes.png"
              class="card-img-top"
              alt="Card image cap"
            />
          </a>
          <b-card-text>
            <h4>Animales Salvajes</h4>
            <small class="muted">
              Ejercicio para Bootcamp de Front End dev in Vue.JS. Es la vista
              para una aplicación que hace seguimiento a algunos animales
              salvajes.
            </small>
          </b-card-text>
          <template #footer>
            Para este ejercicio utilicé HTML, Bootstrap, Javascript y llamado a
            API.
                            <br>
            <button type="button" class="btn btn-outline-secondary">
              <a
                href="https://github.com/Catalinantf/animales-salvajes"
                >Repositorio</a
              >
            </button>
          </template>
        </b-card>
      </b-card-group>
      <b-card-group class="mb-4">
        <!-- card pokeapi -->
        <b-card bg-variant="transparent" border-variant="light">
          <a href="https://dreamy-newton-340520.netlify.app/" target="_blank">
            <img
              class="card-img-top border border-primary border-1"
              src="../assets/pokeguia.png"
              alt="Card image cap"
            />
          </a>
          <b-card-text>
            <h4>Pokeguía</h4>
            <small class="muted">
              Ejercicio para Bootcamp de Front End dev in Vue.JS. Buscador de
              pokemones que muestra su imagen, habilidades y movimientos.
            </small>
          </b-card-text>
          <template #footer>
            Para este ejercicio utilicé HTML, Saas llamada a API y Bootstrap.
                            <br>
            <button type="button" class="btn btn-outline-secondary">
              <a
                href="https://github.com/Catalinantf/pokeguia"
                >Repositorio</a
              >
            </button>
          </template>
        </b-card>
        <!-- card viajes -->
        <b-card bg-variant="transparent" border-variant="light">
          <a href="https://catalinantf.github.io/ViajesChile/" target="_blank">
            <img
              class="card-img-top"
              src="../assets/viajes-chile.png"
              alt="Card image cap"
            />
          </a>
          <b-card-text>
            <h4>Viajes Chile</h4>
            <small class="muted">
              Ejercicio para Bootcamp de Front End dev in Vue.JS. Landing page
              responsiva para agencia de viajes.
            </small>
          </b-card-text>
          <template #footer>
            Para este ejercicio utilicé HTML, CSS Y Bootstrap.
            <br>
                <br>
            <button type="button" class="btn btn-outline-secondary">
              <a
                href="https://github.com/Catalinantf/ViajesChile/"
                >Repositorio</a
              >
            </button>
          </template>
        </b-card>
        <!-- card emprendimiento -->
        <b-card bg-variant="transparent" border-variant="light">
          <a href="https://nervous-edison-578da5.netlify.app/" target="_blank">
            <img
              class="card-img-top"
              src="../assets/mi-empredimiento-web.svg"
              alt="Card image cap"
            />
          </a>

          <b-card-text>
            <h4>Mi Emprendimiento Web 2021</h4>
            <small class="muted">
              Ejercicio para Bootcamp de Front End dev in Vue.JS. Es un sitio
              web responsivo de venta de cursos.
            </small>
          </b-card-text>
          <template #footer>
            Para este ejercicio utilicé HTML, Saas animaciones en CSS y
            Bootstrap.
              <br>
            <button type="button" class="btn btn-outline-secondary" href="https://github.com/Catalinantf/Mi-emprendimiento-web-2021">
              <a
                href="https://github.com/Catalinantf/Mi-emprendimiento-web-2021"
                >Repositorio</a
              >
            </button>
          </template>
        </b-card>
      </b-card-group>
    </b-container>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
};
</script>
<style>
a{
  color: #332b44
}
</style>
