<template>
  <div>
    <main class="Main__Primary">
      <HeaderMenu></HeaderMenu>
      <Nuxt />
       <FooterMenu></FooterMenu>
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
import FooterMenu from '@/components/FooterMenu.vue'
  export default {
    components: {
    HeaderMenu,
    FooterMenu
},
  }
</script>
