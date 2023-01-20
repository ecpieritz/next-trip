<template>
  <section class="nt-support">
    <div class="container-fluid">
      <h2 class="text-center">Do you want to prevent yourself in case something unforeseen arises on your trip?</h2>
      <h3 class="text-center">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce porttitor nibh sit amet ornare.</h3>

      <div class="row">
        <div class="col-lg-4 nt-support__item">
          <img class="nt-color__bg__pink-gradient" src="../assets/imgs/icons/nt-support__call.png" alt="">
          <h4>Support 24/7</h4>
          <p>Suspendisse at nulla at tortor cursus feugiat. Praesent sed auctor felis.</p>
        </div>
        <div class="col-lg-4 nt-support__item">
          <img class="nt-color__bg__blue-gradient" src="../assets/imgs/icons/nt-support__travel-insurance.png" alt="">
          <h4>Travel insurance</h4>
          <p>Suspendisse at nulla at tortor cursus feugiat. Praesent sed auctor felis.</p>
        </div>
        <div class="col-lg-4 nt-support__item">
          <img class="nt-color__bg__yellow-gradient" src="../assets/imgs/icons/nt-support__health.png" alt="">
          <h4>Health insurance</h4>
          <p>Suspendisse at nulla at tortor cursus feugiat. Praesent sed auctor felis.</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'OurSupport',
  props: {
  }
}
</script>

<style scoped lang="scss">
@import '../scss/main.scss';

.nt-support{
  padding-top: 160px;

  h2{
    width: 70%;
    margin: auto;
  }
  
  h3{
    width: 50%;
    margin: 15px auto 80px auto;
  }

  &__item{
    text-align: center;
    padding: 0 20px;
    img{
      width: 120px;
      padding: 30px;
      border-radius: 25px;
      margin-bottom: 30px;
    }
    h4{
      margin-bottom: 10px;
    }

  }

  @media(max-width: 780px){
  }
}
</style>
