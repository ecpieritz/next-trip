<template>
  <nav class="navbar  navbar-expand-lg navbar-dark nt-color__bg__black-gradient">
    <a class="navbar-brand" href="#"><span class="nt-color__text__pink">N</span>ext <span class="nt-color__text__pink">T</span>rip</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="nav justify-content-center collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item active">
          <a class="nav-link" href="#nt-banner">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#nt-about">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#nt-travel">Travels</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#nt-service">Services</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#nt-testimonial">Testimonial</a>
        </li>
      </ul>

    </div>
    <a class="nt-btn bg-pink" href="#nt-contact">Contact Us</a>
  </nav>
</template>

<script>
export default {
  name: 'NavBar',
  props: {
  }
}
</script>

<style scoped lang="scss">
@import '../scss/main.scss';

.navbar{
  padding: 20px 80px;
  .navbar-brand{
    font-weight: 800;
    font-size: 40px;
    color: $nt-white;
  }
  .nav-item{
    &.active{
      .nav-link{
        color: $nt-blue;
      }
    }
    .nav-link{
      color: $nt-white;
      font-size: 18px;
      font-weight: 600;

      &:hover{
        color: $nt-blue;
      }
    }
  }

  .nav{
    justify-content: space-between;
  }

  @media(max-width: 780px){
    padding: 5px 10px;
    .navbar-toggler{
      order: 2;
      border: none;
    }
    .nt-btn{
      order: 1;
    }
    .navbar-brand{
      order: 0;
      font-size: 35px;
    }

    .justify-content-center{
      justify-content: left !important;
      margin: 20px 0;
    }
  }
}
</style>
