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
  page-enter-active {
    transition: opacity .4s ease;
    opacity: 0;
    animation: slide .4s ease;
  }
  .page-enter-to {
    opacity: 1;
  }
  .page-leave-active {
    transition: opacity .4s ease;
    opacity: 1;
    animation: slide .4s ease reverse;
  }
  .page-leave-to {
    opacity: 0;
  }
  @keyframes slide {
    from {
      transform: translateY(50px);
    }
    to {
      transform: translateY(0);
    }
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
