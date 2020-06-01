<template>
  <div>
    <h1>About page</h1>
    <p>This is the best plataform for book lovers</p>
    <div class="my-2">
      <v-btn to="/books" small outlined rounded color="primary">
        Primary
      </v-btn>
    </div>
  </div>
</template>

<script>
export default {
  head () {
    return {
      title: 'About puke.io',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'The best platform for book lovers.'
        }
      ]
    }
  }

}
</script>

<style>

</style>
