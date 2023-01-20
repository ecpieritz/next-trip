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
            <label for="form-message">Message</label>
            <textarea class="form-control" id="form-message" rows="6"></textarea>
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

</style>
