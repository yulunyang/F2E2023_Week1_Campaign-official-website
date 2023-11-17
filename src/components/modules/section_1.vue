<template>
  <div class="section1 container mx-auto flex h-full">
    <!-- <div class="container mx-auto flex h-full max-w-8xl"> -->
      <div class="label1 flex items-center">
        <img src="@/assets/img/label1.png" alt="">
      </div>
      <div class="flex-1 relative">
        <div class="absolute cat1" data-aos="fade-right" data-aos-offset="200">
          <img src="@/assets/img/cat1.png" alt="">
        </div>
        <div class="absolute cat2"  data-aos-delay="200" data-aos="fade-left" data-aos-offset="200">
          <img src="@/assets/img/cat2.png" alt="">
        </div>
        <div class="absolute cat3"  data-aos-delay="400" data-aos="fade-right" data-aos-offset="200">
          <img src="@/assets/img/cat3.png" alt="">
        </div>
        <div class="absolute people1" >
          <img src="@/assets/img/people1.png" alt="">
        </div>
      </div>
    <!-- </div> -->
  </div>
</template>
<script>

export default({
  setup () {
  },
})
</script>

<style lang="scss" scoped>
.section1 {
  height: calc(100vh - 70px);

  background-image: url('~@/assets/img/bg2.png'), url('~@/assets/img/bg1.png');
  background-position: right, center;
  background-repeat: no-repeat;
  background-size: cover;
  @media screen and (max-width: 1440px) {
    height: auto;
    background-position: center, center;
  }
  .label1 {
    max-width: 10%;
    @media screen and (max-width: 768px) {
      max-width: 30%;
    }
  }
  .cat1 {
    left: 8%;
    top: 5%;
    max-width: 15%;
    @media screen and (max-width: 1440px) {
      left: 8%;
      top: 30%;
    }
    // img {
    //   width: 60%;
    // }
  }
  .cat2 {
    left: 35%;
    top: 8%;
    max-width: 15%;
    @media screen and (max-width: 1440px) {
      left: 35%;
      top: 35%;
    }
    // img {
    //   width: 60%;
    // }
  }
  .cat3 {
    left: 20%;
    top: 35%;
    max-width: 25%;
    @media screen and (max-width: 1440px) {
      left: 15%;
      top: 40%;
    }
  }
  .people1 {
    right: 0;
    bottom: 0;
    max-width: 40%;
    width: auto;
    @media screen and (max-width: 768px) {
      max-width: 35%;
      right: 10%;
      bottom: 0;
      max-width: 100%;
    }
  }
}
</style>
