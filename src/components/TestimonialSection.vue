<template>
  <section class="nt-testimonial" id="nt-testimonial">
    <div class="container-fluid">
      <div id="nt-testimonial__carousel" class="carousel slide" data-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <div class="cards-wrapper">
            <div class="card">
              <img src="../assets/imgs/nt-testimonial__01.jpg" class="card-img-top" alt="Dave Nereo">
              <div class="card-body">
                <h5 class="card-title">Dave Nereo</h5>
                <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce porttitor nibh sit amet ornare gravida. In consequat malesuada vehicula. Donec maximus turpis id sapien gravida facilisis. Suspendisse at nulla at tortor cursus feugiat.</p>
              </div>
            </div>
            <div class="card d-none d-md-block">
              <img src="../assets/imgs/nt-testimonial__02.jpg" class="card-img-top" alt="Alexia Emelina">
              <div class="card-body">
                <h5 class="card-title">Alexia Emelina</h5>
                <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce porttitor nibh sit amet ornare gravida. In consequat malesuada vehicula. Donec maximus turpis id sapien gravida facilisis. Suspendisse at nulla at tortor cursus feugiat.</p>
              </div>
            </div>
            <div class="card d-none d-md-block">
              <img src="../assets/imgs/nt-testimonial__03.jpg" class="card-img-top" alt="Fernando Praise">
              <div class="card-body">
                <h5 class="card-title">Fernando Praise</h5>
                <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce porttitor nibh sit amet ornare gravida. In consequat malesuada vehicula. Donec maximus turpis id sapien gravida facilisis. Suspendisse at nulla at tortor cursus feugiat.</p>
              </div>
            </div>
          </div>
          </div>
          <div class="carousel-item">
            <div class="cards-wrapper">
              <div class="card">
                <img src="../assets/imgs/nt-testimonial__04.jpg" class="card-img-top" alt="Gabriela Grazia">
                <div class="card-body">
                  <h5 class="card-title">Gabriela Grazia</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce porttitor nibh sit amet ornare gravida. In consequat malesuada vehicula. Donec maximus turpis id sapien gravida facilisis. Suspendisse at nulla at tortor cursus feugiat.</p>
                </div>
              </div>
              <div class="card d-none d-md-block">
                <img src="../assets/imgs/nt-testimonial__05.jpg" class="card-img-top" alt="Collyn Doriano">
                <div class="card-body">
                  <h5 class="card-title">Collyn Doriano</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce porttitor nibh sit amet ornare gravida. In consequat malesuada vehicula. Donec maximus turpis id sapien gravida facilisis. Suspendisse at nulla at tortor cursus feugiat.</p>
                </div>
              </div>
              <div class="card d-none d-md-block">
                <img src="../assets/imgs/nt-testimonial__06.jpg" class="card-img-top" alt="Jésica Anneka">
                <div class="card-body">
                  <h5 class="card-title">Jésica Anneka</h5>
                  <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce porttitor nibh sit amet ornare gravida. In consequat malesuada vehicula. Donec maximus turpis id sapien gravida facilisis. Suspendisse at nulla at tortor cursus feugiat.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <a class="carousel-control-prev" href="#nt-testimonial__carousel" role="button" data-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#nt-testimonial__carousel" role="button" data-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="sr-only">Next</span>
        </a>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'TestimonialSection',
  props: {
  }
}
</script>

<style scoped lang="scss">
@import '../scss/main.scss';

.nt-testimonial{
  padding: 160px 0;

  .cards-wrapper {
    display: flex;
    justify-content: center;
  }
  .card img {
    max-width: 100%;
    max-height: 100%;
  }
  .card {
    margin: 0 0.5em;
    box-shadow: 2px 6px 8px 0 rgba(22, 22, 26, 0.18);
    border: none;
    border-radius: 0;
  }
  .carousel-inner {
    padding: 1em;
  }
  .carousel-control-prev,
  .carousel-control-next {
    background-color: #e1e1e1;
    width: 5vh;
    height: 5vh;
    border-radius: 50%;
    top: 50%;
    transform: translateY(-50%);
  }
  @media (min-width: 781px) {
    .card img {
      height: 25em;
    }
  }

  @media(max-width: 780px){
    padding: 80px 20px;
  }
}
</style>
