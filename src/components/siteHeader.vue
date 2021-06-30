<template>
  <div class="header">
    <a href="#"> <img src="https://i.ibb.co/MnQ2x6q/10.png" class="logoImg"> </a>
  </div>
</template>

<script>
export default {
  name: 'siteHeader'
}
</script>


<style scoped>
.header {
    padding: 1rem 25rem;
}
.header .logoImg{
    max-width: 375px;
    transition: 350ms;
    transition-timing-function: cubic-bezier(0.68, -0.24, 0.05, 1.65);
}
.logoImg:hover {
    transform: scale(1.04, 1.04);
}
</style>
