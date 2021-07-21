<template>
  <div class="container">
    <h1>About Us</h1>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eaque mollitia
      qui, alias accusamus, doloremque officiis reprehenderit deserunt tempora
      eius nihil reiciendis error? Sit, blanditiis perspiciatis?
    </p>
  </div>
</template>
<script>
export default {
  head() {
    return {
      title: ' Posts | Application Nuxt',
      meta: [
        { charset: 'utf-8' },
        { name: 'viewport', content: 'width=device-width, initial-scale=1' },
        {
          hid: 'description',
          name: 'description',
          content: 'Website about posts',
        },
      ],
      htmlAttrs: { lang: 'en' },
      link: [{ rel: 'icon', type: 'image/x-icon', href: '/favicon.ico' }],
    }
  },
}
</script>
