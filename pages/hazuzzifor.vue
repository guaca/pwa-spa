<template>
  <section class="container">
    <div>
      <nuxt-link to="/">
        <app-logo/>
      </nuxt-link>
      <hr>
      <h1 class="title">
        Hazuzzifor
      </h1>
      <h2 class="subtitle">
        Esta página vamos a indexarla e intentar posicionarla para la keyword inventada Hazuzzifor
      </h2>
      <div class="static-content">
        <p>Actualmente no existe ningún resultado en Google para la keyword <strong>Hazuzzifor</strong>, así que el objetivo será no solo indexar esta página si no que aparezca en resultados de búsqueda.</p>
        <p>Desde esta página, vamos a enlazar a otra subpágina a indexar y posicionar por otra keyword inventada:</p>
          <nuxt-link to="/swepallati" class="button--green">Swepallati</nuxt-link>
          <p>El 19 de julio abrimos el archivo robots.txt para permitir que los bots puedan rastrear e indexar este subdominio. ¿Cuánto tardará Google en rastrear e indexar esta página? Esta versión del experimento, al ser una SPA, debería ser la que más tarde Google en poder rastrear e indexar todos los contenidos.</p>
          <p>¿Los resultados? Los analizaremos a partir del próximo 27 de julio ;) </p>
          <p>Y recuerda que puedes ver las distintas versiones creadas para este experimento en https://pwaexperiments.com</p>
      </div>
    </div>
    <app-footer/>
  </section>
</template>

<script type="text/javascript">
import AppLogo from '~/components/AppLogo.vue'
import AppFooter from '~/components/AppFooter.vue'

export default {
  components: {
    AppLogo,
    AppFooter
  },
  head () {
      return {
        title: 'Hazuzzifor - SPA PWA',
        meta: [
          { hid: 'description', name: 'description', content: 'En esta página trabajamos la keyword inventada Hazuzzifor para comprobar la indexación de contenidos en buscadores de una SPA PWA.' },
          { hid: 'og:title', name: 'og:title', content: 'Hazuzzifor - SPA PWA' },
          { hid: 'og:description', name: 'og:description', content: 'En esta página trabajamos la keyword inventada Hazuzzifor para comprobar la indexación de contenidos en buscadores de una SPA PWA.' }
        ]
      }
    }
}
</script>
