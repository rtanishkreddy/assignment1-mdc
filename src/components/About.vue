<template>
  <div class="about">
    <h1>"This is {{ their_name }}, To Do list developed in Vue.Js to learn Vue.Js”
</h1>
    <p>I loved this Tutorial!!</p>
  </div>
</template>

<script>
export default {
  name: 'About',
  data() {
    return {
      their_name: this.$route.params.name
    }
  }
}
</script>