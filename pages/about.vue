<template>
  <section class="container">
    <h1>About Page</h1>
    <p class="subheading">This is where company info will be put.</p>

    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
  </section>
</template> 

<script>

export default {
    head() {
        return {
            title: 'About Page',
            meta: [
                {name: 'description', content: 'This is about section.'},
                {name: 'keywords', content: 'about info'},
            ]
        }
    }
}
</script>

<style>
</style>