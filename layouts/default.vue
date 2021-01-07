<template>
  <div class="app">
    <Nuxt />

    <client-only>
      <script src="/js/app.js"></script>
    </client-only>
  </div>
</template>

<script>
import $ from 'jquery'

export default {
  mounted() {
    $('.app')
  },
  head() {
    return {
      link: [
        {
          rel: 'stylesheet',
          href: '/css/app.css',
        },
      ],
    }
  },
}
</script>
