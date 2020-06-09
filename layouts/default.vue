<template>
  <div>
    <Navbar />
    <div class="margin">
       <nuxt />
    </div>
   <Footer />
  </div>
</template>

<script>
import Navbar from "@/components/Navbar.vue"
import Footer from "@/components/Footer.vue"
export default {
  components : {
    Navbar,
    Footer
  }
}
</script>

<style scoped>
.margin{
  margin-top: 6vh;
}
@media only screen and (max-width: 600px) {
  .margin{
  margin-top: 12vh;
}
}

</style>