<template>
  <div>
    <h1>Books</h1>
    <div class="my-2">
      <nuxt-link to="/about">
        <v-btn small outlined rounded color="primary">
          Primary
        </v-btn>
      </nuxt-link>
    </div>
  </div>
</template>

<script>
export default {
  head () {
    return {
      title: 'Books List',
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
