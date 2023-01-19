<template>
  <section class="nt-about" id="nt-about">
    <div class="container-fluid">
      <div class="row">
        <div class="col-lg-6">
          <div class="nt-about__description">
            <h2>More About Us</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </div>

          <div class="nt-about__prices">
            <div class="nt-about__prices__card">
              <span>From</span>
              <p>$99.00</p>
              <span>Up To</span>
              <p>$5990.00</p>
            </div>
          </div>
        </div>

        <div class="col-lg-6">
          <div class="nt-about__item">
            <img class="nt-color__bg__pink-gradient" src="../assets/imgs/icons/nt-about__cruises.png" alt="white ship">
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. </p>
          </div>
          <div class="nt-about__item">
            <img class="nt-color__bg__pink-gradient" src="../assets/imgs/icons/nt-about__flight.png" alt="white globe with airplane">
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. </p>
          </div>
          <div class="nt-about__item">
            <img class="nt-color__bg__pink-gradient" src="../assets/imgs/icons/nt-about__suitcase.png" alt="white luggage">
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. </p>
          </div>
          <div class="nt-about__item">
            <img class="nt-color__bg__pink-gradient" src="../assets/imgs/icons/nt-about__passport.png" alt="white passport">
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'AboutSection',
}
</script>

<style scoped lang="scss">
@import '../scss/main.scss';

.nt-about {
  padding-top: 160px;

  &__description{
    p{
      margin: 40px 0;
      width: 80%;

      @media(max-width: 780px){
        width: 100%;
      }
    }
  }

  &__prices{
    width: 80%;
    &__card{
      background-color: $nt-blue;
      width: fit-content;
      padding: 20px 40px;
      margin: auto;
      text-align: center;
      line-height: 1.2;
      border-radius: 16px;
      
      span{
        color: $nt-white;
      }

      p{
        color: $nt-yellow;
        font-size: 40px;
        font-weight: 700;
      }

    }

    @media(max-width: 780px){
      width: 100%;
      margin-bottom: 40px;
    }
  }

  &__item{
    display: flex;
    align-items: center;
    margin: 0 0 40px;
    img{
      padding: 20px;
      width: 100px;
      margin-right: 30px;
      border-radius: 20px;
    }

    @media(max-width: 780px){
      margin: 0 0 30px;
      img{
        margin-right: 20px;
        width: 80px;
      }
    }
  }
  @media(max-width: 780px) {
    padding: 80px 20px 0;
  }
}
</style>
