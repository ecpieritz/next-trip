<template>
  <div class="nt-banner">
    <div class="container-fluid">
      <div class="nt-color__bg__white">
        <h1>Your trip starts right here</h1>
        <h4>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
          dolore magna aliqua. Ut enim ad minim veniam.</h4>

        <a class="nt-btn bg-pink" href="#nt-contact">Contact Us</a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeroBanner'
}
</script>

<style scoped lang="scss">
@import '../scss/main.scss';

.nt-banner {
  height: 700px;
  background-image: url(../assets/imgs/nt__banner.png);
  background-repeat: no-repeat;
  background-position: right center;
  background-size: auto 700px;

  .container-fluid {
    padding-top: 8%;
    
  }

  .nt-color__bg__white {
    width: 70%;
    padding: 40px 80px 60px;
    border-radius: 20px;
  }

  h4{
    margin: 40px 0 60px;
    width: 70%;
    line-height: 1.5;
  }

  @media(max-width: 780px) {
    height: auto;
    .nt-color__bg__white{
      width: 100%;
      background-color: transparent;
      padding: 20px 20px 60px;
      
      h1,h4{
        color: $nt-white;
        width: 100%;
      }
    }
  }
}
</style>
