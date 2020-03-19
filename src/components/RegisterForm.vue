<template>
  <section class="register-section background-gradient ptb100">
    <div class="row flex-center">
      <div class="container q-px-lg">
        <div class="row">
          <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12 wow fadeInLeft">
            <div class="reg-wrapper">
              <div class="title-bl text-left">
                <div class="title color-white">Register for our Newsletter now</div>
                <div class="subtitle">Newslatter</div>
              </div>
              <div class="color-white">We are always ready to welcome you!</div>
            </div>
          </div>
          <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12 wow fadeInRight" data-wow-duration="2s">
            <form action="#" class="reg-form">
              <div class="reg_input">
                <input type="text" placeholder="Enter your Email address here" />
              </div>
              <button class="reg_submit">
                <i class="fa fa-envelope color-1 fsize-14" aria-hidden="true"></i>
              </button>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "RegisterForm"
};
</script>