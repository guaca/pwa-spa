<template>
  <section class="container">
    <div>
      <nuxt-link to="/">
        <app-logo/>
      </nuxt-link>
      <hr>
      <h1 class="title">
        Swepallati
      </h1>
      <h2 class="subtitle">
        Esta página vamos a indexarla e intentar posicionarla para la keyword inventada Swepallati
      </h2>
      <app-content/>
      <div class="static-content">
        <p>Actualmente no existe ningún resultado en Google para la keyword <strong>Swepallati</strong>, así que el objetivo será no solo indexar esta página si no que aparezca en resultados de búsqueda.</p>
        <p>El jueves 19 de julio eliminamos el bloqueo en el robots.txt para permitir que los bots puedan rastrear e indexar esta página. ¿Cuánto tardará Google en rastrearla e indexarla? Esta versión del experimento, al ser una SPA, debería ser la que más tarde Google en poder rastrear correctamente e indexar todos los contenidos.</p>
        <p>¿Los resultados? Los veremos a partir del próximo 27 de julio. Stay tuned! ;) </p>
        <p>Recuerda que puedes ver todas las versiones disponibles de este experimento en https://pwaexperiments.com</p>
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
        title: 'Wekilinest',
        meta: [
          { hid: 'description', name: 'description', content: 'En esta página trabajamos la keyword inventada Wekilinest para comprobar la indexación de contenidos en buscadores de una SSR PWA.' },
          { hid: 'og:title', name: 'og:title', content: 'Wekilinest' },
          { hid: 'og:description', name: 'og:description', content: 'En esta página trabajamos la keyword inventada Wekilinest para comprobar la indexación de contenidos en buscadores de una SSR PWA.' }
        ]
      }
    }
}
</script>
