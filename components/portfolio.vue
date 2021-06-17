<template>
  <v-container>
    <div id="component-profile" class="d-flex flex-column justify-center align-center">
      <img src="~assets/img/img.jpg" alt="">
      <h1>{{name}}</h1>
      <h4>{{description}}</h4>
      <div class="d-flex mt-2">
        <a href="https://sunjida-promy.medium.com/" target="blank" title="medium"><i class="fab fa-medium-m mx-2"></i></a>
        <a href="https://www.linkedin.com/in/sunjida-promy-0856aa18a/" target="blank" title="linkedin"><i class="fab fa-linkedin mx-2"></i></a>
        <a href="mailto:sunjida.promy@gmail.com" target="blank" title="medium"><i class="far fa-envelope mx-2"></i></a>
      </div>
    </div>
   </v-container>
</template>

<script>
export default {
  data(){
    return {
      name: "Sunjida Promy",
      description: "I am a front end developer"
    }
  }
}
</script>

<style scoped lang="scss">
#component-profile {
    height: 100vh;
    img {
        max-height: 100px;
        border-radius: 100px;
    }
    i{
        font-size: 34px;
        color: orange;
    }
}
</style>