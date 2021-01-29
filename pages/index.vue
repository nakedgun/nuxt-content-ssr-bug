<template>
  <section class="section">
    <div class="columns is-mobile">
      <h1>Articles (content api):</h1>
<!--      <pre>{{ articles }}</pre>-->
    </div>
  </section>
</template>

<script>
export default {
  name: 'HomePage',
  components: {},
  async asyncData({ $content }) {
    // const articles = await $content('articles')
    //   .only(['title'])
    //   .sortBy('publishedAt', 'desc')
    //   .limit(4)
    //   .fetch()
    // return {
    //   articles,
    // }
  },
}
</script>
