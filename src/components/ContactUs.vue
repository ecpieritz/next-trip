<template>
  <div class="nt-contact" id="nt-contact">
    <div class="container-fluid">
      <div class="nt-color__bg__white">
        <h1>Contact Us</h1>

        <form>
          <div class="form-row">
            <div class="form-group col-md-6">
              <label for="inputName">Name</label>
              <input type="text" class="form-control" id="inputName">
            </div>
            <div class="form-group col-md-6">
              <label for="inputEmail">Email</label>
              <input type="email" class="form-control" id="inputEmail">
            </div>
          </div>
          <div class="form-group">
            <label for="formMessage">Message</label>
            <textarea class="form-control" id="formMessage" rows="6"></textarea>
          </div>
          <button type="submit" class="nt-btn bg-pink">Send</button>
        </form>

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

.nt-contact {
  height: 800px;
  background-image: url(../assets/imgs/nt__contact-bg.png);
  background-repeat: no-repeat;
  background-position: right center;
  background-size: auto 800px;

  .container-fluid {
    padding-top: 8%;

  }

  .nt-color__bg__white {
    width: 60%;
    padding: 40px 80px 60px;
    border-radius: 20px;
  }

  .form-group{
    margin-top: 20px;
    label{
      margin: 0;
      font-size: 20px;
    }

    &.col-md-6{
      padding-left: 0;
      padding-right: 0;
      &:first-child{
        padding-right: 5px;
      }
    }
  }

  button{
      margin-top: 40px;
  }

  @media(max-width: 780px) {
    height: auto;

    .nt-color__bg__white {
      width: 100%;
      background-color: transparent;
      padding: 20px 20px 60px;

      h1 {
        color: $nt-white;
        width: 100%;
      }
    }
  }
}
</style>
