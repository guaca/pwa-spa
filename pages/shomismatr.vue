<template>
  <section class="container">
    <div>
      <nuxt-link to="/">
        <app-logo/>
      </nuxt-link>
      <hr>
      <h1 class="title">
        Shomismatr
      </h1>
      <h2 class="subtitle">
        Esta página vamos a indexarla e intentar posicionarla para la keyword inventada Shomismatr
      </h2>
      <div class="static-content">
        <p>Actualmente no existe ningún resultado en Google para la keyword <strong>Shomismatr</strong>, así que el objetivo será no solo indexar esta página en Google si no que aparezca en resultados de búsqueda.</p>
        <p>Desde esta página, vamos a enlazar a otra subpágina a indexar y posicionar por otra keyword inventada:</p>
        <nuxt-link to="/gophoeminu" class="button--green">Gophoeminu</nuxt-link>
        <p>El 19 de julio de 2018 permitimos que los bots puedan rastrear e indexar esta página. ¿Cuánto tardará Google en rastrear e indexar estos contenidos? Esta versión del experimento, al ser una Single Page Application, debería ser la que más tarde Google en poder rastrear e indexar.</p>
        <p>Los primeros resultados los veremos el próximo 27 de julio en el evento SEOPLUS ;) </p>
        <p>Recuerda que puedes navegar entre todas las versiones de este experimento desde https://pwaexperiments.com</p>
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
        title: 'Shomismatr - SPA PWA',
        meta: [
          { hid: 'description', name: 'description', content: 'En esta página trabajamos la keyword inventada Shomismatr para comprobar la indexación de contenidos en buscadores de una SPA PWA.' },
          { hid: 'og:title', name: 'og:title', content: 'Shomismatr - SPA PWA' },
          { hid: 'og:description', name: 'og:description', content: 'En esta página trabajamos la keyword inventada Shomismatr para comprobar la indexación de contenidos en buscadores de una SPA PWA.' }
        ]
      }
    }
}
</script>
