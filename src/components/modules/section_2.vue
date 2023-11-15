<template>
  <div class="section2 py-32 md:py-0 px-4 overflow-hidden h-full flex items-center">
    <div class="flex flex-wrap justify-center items-center container mx-auto h-full max-w-8xl">
      <div class="w-full md:w-2/5 people2 order-2 md:order-1">
        <img src="@/assets/img/people2.png" alt="">
      </div>
      <div class="w-full md:w-3/5 order-1 md:order-2">
        <p class="proj-text-third text-2xl opacity-25 mb-0">Who am I</p>
        <div class="signName mb-3 px-3">
          <img src="@/assets/img/signName.png" alt="" class="border-b">
        </div>

        <p class="proj-text-fourth font-bold mb-4 text-lg">護航台灣的幸福經濟，從照顧每一隻貓咪開始。</p>
        <p class="proj-text-primary font-bold">台灣民眾的身心健康與工作熱情是推動經濟的核心動力，<br/>透過完善的貓咪福利政策，即可為台灣的 GDP 經濟帶來巨大效益。<br/><br/>因此，我期望能在立法院內推進相關政策，<br/>確保每一隻貓咪都能得到他們應有的照顧，同時也為台灣的經濟發展助一臂之力。</p>
        <p class="proj-text-primary font-bold">讓我們藉由推動更完善的貓咪福利和政策，間接地投資 <span class="proj-text-fourth">台灣的未來 !</span></p>
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
  .section2 {
    min-height: calc(100vh - 70px);
    width: 100%;
    background-image: url('~@/assets/img/cat_hand1.png'), url('~@/assets/img/cat_hand2.png'), url('~@/assets/img/cat_hand3.png'), url('~@/assets/img/cat_hand4.png'), url('~@/assets/img/footlabel.png');
    background-position: left top, right top, left bottom, right bottom, right 10% bottom -20%;
    background-repeat: no-repeat;
    // background-size: contain;
    @media screen and (max-width: 768px) {
      background-size: 20%;
    }
  }
</style>
