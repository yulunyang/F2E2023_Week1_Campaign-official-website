<template>
  <footer class="w-full proj-bg-primary p-4 overflow-hidden">
    <div class="container mx-auto py-10 md:py-12 flex flex-wrap">
      <div class="w-full md:w-1/2 flex flex-wrap mb-8">
        <p class="text-white text-7xl md:text-8xl font-bold mr-12 mb-6 md:mb-0">喵?</p>
        <ul class="text-white text-sm list-disc list-inside leading-loose">
          <li>辦公室地址：喵星區，毛茸茸大道88號，喵喵大樓3樓</li>
          <li>電話：(02) 888-5678</li>
          <li>電子郵件地址：meowoffice@linmeow.tw</li>
        </ul>
      </div>
      <div class="w-full md:w-1/2 text-sm">
        <div class="flex items-center text-white">
          <a href="">首頁</a>
          <span class="mx-4">-</span>
          <a href="">最新活動</a>
          <span class="mx-4">-</span>
          <a href="">政策議題</a>
          <span class="mx-4">-</span>
          <a href="">小額捐款</a>
        </div>
        <div class="flex mt-8">
          <p class="text-white mr-8">社群媒體</p>
          <a href=""><img src="@/assets/img/social.png" alt=""></a>
        </div>
      </div>
    </div>
    <div class="flex justify-end">
      <p class="text-white text-xs font-bold">© 2023 [立委候選人姓名] 版權所有。</p>
    </div>
  </footer>
</template>
<script>

export default({
  setup () {
  },
})
</script>

<style lang="scss" scoped>
header {
  background: white;
  // box-shadow: 0px 1px 4px 0px #856A4280;
  .button {
    // height: 35px;
    // width: 104px;
    color: white;
    background: #7d6035;
    // &:hover {
    //   box-shadow:
    //     inset 0.3em 0.3em 0 0 #3C0C00;
    // }
    // &:active {
    //   background: #3C0C00;
    // }
    // &:focus {
    //   color: #B82A06;
    //   background: #FFFFFF;
    // }
    // +.disabled {
    //   color: #FFFFFF;
    //   background: #DCDCDC;
    // }
  }
}
</style>
