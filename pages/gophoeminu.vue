<template>
  <section class="container">
    <div>
      <nuxt-link to="/">
        <app-logo/>
      </nuxt-link>
      <hr>
      <h1 class="title">
        Gophoeminu
      </h1>
      <h2 class="subtitle">
        Esta página vamos a indexarla e intentar posicionarla para la keyword inventada Gophoeminu
      </h2>
      <app-content/>
      <div class="static-content">
        <p>Actualmente no existe ningún resultado en Google para la keyword <strong>Gophoeminu</strong>, así que el objetivo será no solo indexar esta página si no que aparezca en resultados de búsqueda.</p>
        <p>El 19 de julio de 2018 abrimos el robots.txt para permitir que los bots puedan rastrear e indexar esta página. ¿Cuánto tardará Google en rastrearla e indexarla? Esta versión del experimento, al ser una SPA, debería ser la que más tarde Google en poder rastrear correctamente e indexar todos los contenidos.</p>
        <p>¿Los resultados? Los veremos a partir del próximo 27 de julio ;) </p>
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
        title: 'Kicalithno',
        meta: [
          { hid: 'description', name: 'description', content: 'En esta página trabajamos la keyword inventada Kicalithno para comprobar la indexación de contenidos en buscadores de una SSR PWA.' },
          { hid: 'og:title', name: 'og:title', content: 'Kicalithno' },
          { hid: 'og:description', name: 'og:description', content: 'En esta página trabajamos la keyword inventada Kicalithno para comprobar la indexación de contenidos en buscadores de una SSR PWA.' }
        ]
      }
    }
}
</script>
