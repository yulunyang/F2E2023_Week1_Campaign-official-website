<template>
  <div class="section1">
    <div class="container mx-auto flex h-full max-w-8xl">
      <div class="label1 flex items-center">
        <img src="@/assets/img/label1.png" alt="">
      </div>
      <div class="flex-1 relative">
        <div class="absolute cat1">
          <img src="@/assets/img/cat1.png" alt="">
        </div>
        <div class="absolute cat2">
          <img src="@/assets/img/cat2.png" alt="">
        </div>
        <div class="absolute cat3">
          <img src="@/assets/img/cat3.png" alt="">
        </div>
        <div class="absolute people1">
          <img src="@/assets/img/people1.png" alt="">
        </div>
      </div>
    </div>
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
  height: calc(100vh - 56px);
  background-image: url('~@/assets/img/bg2.png'), url('~@/assets/img/bg1.png');
  background-position: right, center;
  background-repeat: no-repeat;
  background-size: contain;
  .label1 {
    // width: 70%;
    img {
      width: 70%;
    }
  }
  .cat1 {
    left: 8%;
    top: 5%;
    img {
      width: 60%;
    }
  }
  .cat2 {
    left: 35%;
    top: 8%;
    img {
      width: 60%;
    }
  }
  .cat3 {
    left: 20%;
    top: 30%;
    img {
      width: 60%;
    }
  }
  .people1 {
    right: 0;
    bottom: 0;
    // width: 70%;
    img {
      width: 70%;
    }
  }
}
</style>
