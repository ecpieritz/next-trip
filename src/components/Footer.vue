<template>
  <footer class="nt-footer nt-color__bg__black-gradient" id="nt-footer">
    <div class="row">
      <div class="col-md-4 nt-footer__brand">
        <a href="#"><span class="nt-color__text__pink">N</span>ext <span
          class="nt-color__text__pink">T</span>rip</a>

        </div>
        <div class="col-md-4 nt-footer__menu">
          <h4 class="nt-color__text__pink">Menu</h4>
          <a href="#nt-about">About</a>
          <a href="#nt-travel">Travels</a>
          <a href="#nt-service">Services</a>
          <a href="#nt-testimonial">Testimonial</a>
        </div>
        <div class="col-md-4 nt-footer__address">
          <h4 class="nt-color__text__pink">Our Infos</h4>
          <p>São Paulo Street, 1234<br/>Blumenau/SC - Brazil</p>
          <p>info@yourdomain.com</p>
          <p>+55 (00) 00000-0000</p>
        </div>
      </div>

      <h4 class="nt-footer__made-by">© 2022 Made with 💙 by Emilyn C. Pieritz</h4>
    </footer>
</template>

<script>
export default {
  name: 'FooterNt'
}
</script>

<style scoped lang="scss">
@import '../scss/main.scss';

.nt-footer {
  padding: 20px 80px;
  
  &__made-by{
    margin-top: 40px;
    color: $nt-white;
    text-align: center;
  }

  &__brand {
    font-size: 50px;
    line-height: 1;
    display: flex;
    flex-direction: column;

    a{
      text-decoration: none;
      color: $nt-white;
      font-weight: 700;
    }

  }

  &__menu{
    display: flex;
    flex-direction: column;
    text-align: center;
    font-size: 18px;

    h4{
      margin-bottom: 20px;
    }
    
    a{
      margin: 3px 0;
      color: $nt-white;
      text-decoration: none;
      
      &:hover{
        color: $nt-blue;
      }
    }
  }

  &__address{
    text-align: end;
    h4{
      margin-bottom: 20px;
    }
    p{
      margin: 10px 0;
    }
  }


  p {
    color: $nt-white;
  }

  @media(max-width: 780px) {}
}
</style>
