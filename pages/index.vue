<template>
  <section class="container">
    <h1>Demo Site for Stone</h1>
    <p class="subheading">This is the Demo Site for Stone.</p>

    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. A amet maxime esse, recusandae libero veniam dolorum doloremque deserunt nihil magni adipisci assumenda quaerat mollitia, ipsam minima, possimus architecto? Ut, porro.</p>
  </section>
</template> 

<script>

export default {
    head() {
        return {
            title: 'Stone Home',
            meta: [
                {name: 'description', content: 'This is about section.'},
                {name: 'keywords', content: 'about info'},
            ]
        }
    }

}
</script>

<style>
/*.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; '/* 1 *'/
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
} 
*/
</style> 


