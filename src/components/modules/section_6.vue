<template>
  <div class="section6">
    <div class="max-w-3xl mx-auto px-4">
      <div class="flex justify-between items-center">
        <div></div>
        <p class="text-3xl md:text-5xl font-bold proj-text-primary">服務信箱</p>
        <div class="w-2/5 md:w-auto">
          <img src="@/assets/img/mailbox2.png" alt="">
        </div>
      </div>
      <div class="flex items-center justify-center text-5xl w-full max-w-xl mx-auto">
        <div class="relative flex flex-col rounded-xl bg-transparent bg-clip-border text-gray-700 shadow-none w-full">
          <form class="mt-8 mb-2 w-full">
            <div class="mb-4 flex flex-col gap-6">
              <div class="mb-2 relative">
                <label class="block text-sm proj-text-primary font-bold" for="username">姓名 :</label>
                <input type="email" class="proj-border-secondary text-sm appearance-none border rounded w-full py-3 px-3 textColorDarkBlack leading-tight focus:outline-none focus:border-gray-900"
                  id="username" placeholder="請填入您的大名或暱稱，讓我們知道該如何稱呼您" autocomplete="off" name="name" />
              </div>
              <div class="mb-2 relative">
                <label class="block text-sm proj-text-primary font-bold" for="username">手機 :</label>
                <input type="email" class="proj-border-secondary text-sm appearance-none border rounded w-full py-3 px-3 textColorDarkBlack leading-tight focus:outline-none focus:border-gray-900"
                  id="username" placeholder="有任何想法我們會以來電方式向您聯繫" autocomplete="off" name="phone" />
              </div>
              <div class="mb-2 relative">
                <label class="block text-sm proj-text-primary font-bold" for="username">信箱 :</label>
                <input type="email" class="proj-border-secondary text-sm appearance-none border rounded w-full py-3 px-3 textColorDarkBlack leading-tight focus:outline-none focus:border-gray-900"
                  id="username" placeholder="寄出後我們會以信件方式向您通知目前的讀取狀況" autocomplete="off" name="mail" />
              </div>
              <div class="mb-2 relative">
                <label class="block text-sm proj-text-primary font-bold" for="username">建言 :</label>
                <textarea name="" id="" cols="25" rows="10" class="proj-border-secondary text-sm appearance-none border rounded w-full py-3 px-3 textColorDarkBlack leading-tight focus:outline-none focus:border-gray-900"></textarea>
              </div>
            </div>
            <div class="flex justify-between items-center flex-wrap">
              <div class="flex items-center">
                <div class="flex items-center mr-3">
                  <label class="block text-sm proj-text-primary font-bold whitespace-nowrap mr-2" for="code">驗證碼 :</label>
                  <input type="email" class="proj-border-secondary text-sm appearance-none border rounded py-3 px-3 textColorDarkBlack leading-tight focus:outline-none focus:border-gray-900"
                    id="username" placeholder="" autocomplete="off" name="code" />
                </div>
                <div class="flex flex-col justify-center">
                  <div class="">
                    <img src="@/assets/img/code.png" alt="">
                  </div>
                  <a href="" class="proj-texr-fifth whitespace-nowrap text-xs">換一張</a>
                </div>
              </div>
              <div class="w-full md:w-auto mt-6 md:mt-0">

                <button
                  class="block w-full select-none rounded proj-bg-primary py-3 px-16 text-center align-middle text-xs font-bold uppercase text-white shadow-md transition-all"
                  type="button"
                  data-ripple-light="true"
                  >信件送出
              </button>
              </div>
            </div>
          </form>
        </div>
      </div>
    </div>
    <div data-aos="fade-right" data-aos-offset="200">
      <img src="@/assets/img/cat8.png" alt="">
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
  .section6 {
    // height: calc(100vh - 70px);
    width: 100%;
  }
</style>
