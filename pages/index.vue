<template>
  <div class="container">
    <div>
      <nuxt-link to="about">About page</nuxt-link> <br>
      <h2>Mq Component</h2>
      <mq-component />

      <hr>
      <h2>Mq Component 2</h2>
      <mq-component2 />
    </div>
  </div>
</template>

<script>
export default {
  components: {
    MqComponent: () => import('~/components/MqComponent'),
    MqComponent2: () => import('~/components/MqComponent2')
  },
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
