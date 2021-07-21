<template>
  <h1>Welcome to my first NuxtJS app</h1>
</template>

<script>
export default {
  head() {
    return {
      title: 'Application Nuxt Posts | Home',
      meta: [
        { charset: 'utf-8' },
        { name: 'viewport', content: 'width=device-width, initial-scale=1' },
        { hid: 'description', name: 'description', content: 'Website about posts' },

      ],
      htmlAttrs: { lang: 'en' },
      link: [{ rel: 'icon', type: 'image/x-icon', href: '/favicon.ico' }],
    }
  },
}
</script>
