<template>
  <div>
    <main class="Main__Primary">
      <Nuxt />
    </main>
  </div>
</template>
<style lang="scss">
  .Main__Primary {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
  }
</style>

<script>
import HeaderMenu from '@/components/HeaderMenu.vue'
  export default {
    components: {
    HeaderMenu
  },
    data() {
      return {
        img1: 'Logo',
        img2: 'Logo2',
        img3: 'account',
      }
    }
  }
</script>
