<template>
  <section class="nt-support">
    <div class="container-fluid">
      <h2 class="text-center">Do you want to prevent yourself in case something unforeseen arises on your trip?</h2>
      <h3 class="text-center">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce porttitor nibh sit amet ornare gravida. In consequat malesuada vehicula. Donec maximus turpis id sapien gravida facilisis.</h3>

      <div class="row">
        <div class="col-lg-4">
          <img src="../assets/imgs/icons/nt-support__call.png" alt="">
          <h4>Support 24/7</h4>
          <p>Suspendisse at nulla at tortor cursus feugiat. Praesent sed auctor felis.</p>
        </div>
        <div class="col-lg-4">
          <img src="../assets/imgs/icons/nt-support__travel-insurance.png" alt="">
          <h4>Travel insurance</h4>
          <p>Suspendisse at nulla at tortor cursus feugiat. Praesent sed auctor felis.</p>
        </div>
        <div class="col-lg-4">
          <img src="../assets/imgs/icons/nt-support__health.png" alt="">
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

  @media(max-width: 780px){
    
  }
}
</style>
