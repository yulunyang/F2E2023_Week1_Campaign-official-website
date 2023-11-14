<template>
  <header class="z-50 shadow-md fixed w-full top-0 left-0">
    <div class="container mx-auto py-2 px-2 flex justify-end">
      <div class="flex justify-between w-full items-center">
        <div class="flex items-center">
          <p class="proj-text-primary">競選倒數：</p>
          <div class="flex-col justify-center items-center mx-3">
            <p class="proj-text-primary font-semibold">40</p>
            <p class="proj-text-secondary text-xs">DAY</p>
          </div>
          <div class="flex-col justify-center items-center mx-3">
            <p class="proj-text-primary font-semibold">03</p>
            <p class="proj-text-secondary text-xs">HOUR</p>
          </div>
          <div class="flex-col justify-center items-center mx-3">
            <p class="proj-text-primary font-semibold">33</p>
            <p class="proj-text-secondary text-xs">MIN</p>
          </div>
        </div>
        <div class="flex items-center">
          <a href="https://2022.thef2e.com/login" target="_blank" class="py-2 px-3 inline-flex items-center justify-center mr-3 cursor-pointer text-sm tracking-wider proj-text-primary">委員介紹</a>
          <a href="https://2022.thef2e.com/login" target="_blank" class="py-2 px-3 inline-flex items-center justify-center mr-3 cursor-pointer text-sm tracking-wider proj-text-primary">競選主張</a>
          <a href="https://2022.thef2e.com/login" target="_blank" class="py-2 px-3 inline-flex items-center justify-center mr-3 cursor-pointer text-sm tracking-wider proj-text-primary">最新消息</a>
          <a href="https://2022.thef2e.com/login" target="_blank" class="py-2 px-3 inline-flex items-center justify-center button mr-3 cursor-pointer text-sm tracking-wider rounded-3xl">小額捐款
            <img src="@/assets/img/heart.png" alt="heart" class="ml-2">
          </a>
          <a href="https://2022.thef2e.com/signup" target="_blank" class="py-2 px-3 inline-flex items-center justify-center button cursor-pointer text-sm tracking-wider rounded-3xl">服務信箱
            <img src="@/assets/img/mailbox.png" alt="mailbox" class="ml-2">
          </a>
        </div>
      </div>
    </div>
  </header>
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
