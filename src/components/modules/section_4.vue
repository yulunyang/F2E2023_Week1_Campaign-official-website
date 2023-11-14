<template>
  <div class="section4 container mx-auto">
    <div class="flex justify-center items-center font-bold proj-text-primary text-xl h-full">
      <p class="mr-20">台灣的明天</p>
      <div class="relative">
        <p>喵先鋪路</p>
        <div class="absolute foot">
          <img src="@/assets/img/foot.png" alt="">
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
  .section4 {
    height: calc(100vh - 56px);
    width: 100%;
    background-image: url('~@/assets/img/cat4.png'), url('~@/assets/img/cat5.png');
    background-position: left 20% top 20%, right 20% bottom 20%;
    background-repeat: no-repeat;
    background-size: 10em;
    .foot {
      right: -70%;
      top: -200%;
    }
  }
</style>
