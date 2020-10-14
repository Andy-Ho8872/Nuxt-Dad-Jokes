<template>
<div>
  <h1>Hello This is dad jokes</h1>
  <p> We are providing some Dad Joke to throw you a wet blaket </p>
</div>
  
</template>

<script>
export default {
  // The head() fucntion is to set mata tag which makes a great impact on SEO
  head() {
    return {
      title: 'About Dad Jokes House', // title tag
      meta: [
        {
          hid: 'description',
          name: 'description', /// description tag
          content: 'A nice place to hear some dad jokes '
        }
      ]
    }
  }
}
</script>

<style>

</style>