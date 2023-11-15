<template>
  <div class="section3 py-20 container mx-auto max-w-7xl overflow-hidden px-4">
    <div class="item1 flex flex-wrap mb-12 justify-center items-center">
      <div class="w-full md:w-3/4">
        <p class="proj-text-primary opacity-60 text-xl font-semibold mb-3">政策一</p>
        <p class="proj-text-primary text-4xl font-black">為毛孩子謀福利！推動 <span class="proj-text-fourth">寵物醫療保障方案</span></p>
        <ul class="mt-12 md:mt-20 list-inside list-decimal proj-text-primary">
          <li class="proj-text-primary font-black mb-3"><span class="proj-text-fourth">設立寵物醫療基金</span>：每年撥款新台幣 10 億元，專款專用於支援家庭寵物的醫療費用</li>
          <li class="proj-text-primary font-black mb-3"><span class="proj-text-fourth">提供醫療補助</span>：每隻寵物每年可獲得高達新台幣 20,000 元的醫療補助，減輕飼主的經濟壓力</li>
          <li class="proj-text-primary font-black mb-3"><span class="proj-text-fourth">合作動物醫院</span>：目前已有和超過 200 家動物醫院進行初步的合作討論</li>
        </ul>
      </div>
      <div class="w-full md:w-1/4">
        <img src="@/assets/img/section3_1.png" alt="">
      </div>
    </div>
    <div class="footlabel flex justify-start w-full">
      <div>
        <img src="@/assets/img/footlabel.png" alt="">
      </div>
    </div>
    <div class="item2 flex flex-wrap mb-12 justify-center items-center">
      <div class="w-full md:w-1/4 order-2 md:order-1">
        <img src="@/assets/img/section3_2.png" alt="">
      </div>
      <div class="w-full md:w-3/4 flex justify-end order-1 md:order-2">
        <div>
          <p class="proj-text-primary opacity-60 text-xl font-semibold mb-3">政策二</p>
          <p class="proj-text-primary text-4xl font-black">打造休閒天堂！推廣 <span class="proj-text-fourth">寵物休閒與娛樂場所</span></p>
          <ul class="mt-12 md:mt-20 list-inside list-decimal proj-text-primary">
            <li class="proj-text-primary font-black mb-3"><span class="proj-text-fourth">建立寵物公園</span>：每年撥款新台幣 5 億元，用於在各大都市建立專屬的寵物公園。根據初步規劃，預計在第一年內，將在全國範圍內建立至少 10 座寵物公園</li>
            <li class="proj-text-primary font-black mb-3"><span class="proj-text-fourth">推廣寵物友善商家</span>：鼓勵商家提供寵物友善的環境，並為參與的商家提供稅收優惠。預計在政策實施後的首年，將有超過 500 家商家加入此計畫</li>
            <li class="proj-text-primary font-black mb-3"><span class="proj-text-fourth">舉辦寵物活動和工作坊</span>：與各大寵物社團和組織合作，每年舉辦至少 5 場大型的寵物活動，包括寵物才藝比賽、飼養知識工作坊等</li>
          </ul>
        </div>
      </div>
    </div>
    <div class="footlabe2 flex justify-end w-full">
      <div>
        <img src="@/assets/img/footlabel.png" alt="">
      </div>
    </div>
    <div class="item3 flex flex-wrap mb-12 justify-center items-center">
      <div class="w-full md:w-3/4">
        <p class="proj-text-primary opacity-60 text-xl font-semibold mb-3">政策三</p>
        <p class="proj-text-primary text-4xl font-black">推廣 <span class="proj-text-fourth">寵物飼養教育</span>，讓愛更加專業</p>
        <ul class="mt-12 md:mt-20 list-inside list-decimal proj-text-primary">
          <li class="proj-text-primary font-black mb-3"><span class="proj-text-fourth">建立寵物飼養教育中心</span>：每年撥款新台幣 3 億元，用於在全國各地建立專業的寵物飼養教育中心。預計在第一年內，在全國至少 5 大城市設立教育中心。</li>
          <li class="proj-text-primary font-black mb-3"><span class="proj-text-fourth">推廣寵物飼養課程</span>：與學校、社區組織和寵物社團合作，推出一系列免費的寵物飼養課程。預計每年將有超過 10,000 名市民受益。</li>
          <li class="proj-text-primary font-black mb-3"><span class="proj-text-fourth">製作教育資料</span>：出版寵物飼養手冊、影片和線上課程，讓所有有意飼養寵物的家庭都能輕鬆取得正確的知識</li>
        </ul>
      </div>
      <div class="w-full md:w-1/4">
          <img src="@/assets/img/section3_3.png" alt="">
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
  .section3 {
    width: 100%;
    .footlabel {
      img {
        width: 80%;
        transform: rotate(-14deg);
      }
    }
    .footlabe2 {
      // transform: rotate(48deg);
      img {
        width: 80%;
        transform: rotate(48deg);
      }
    }
  }
</style>
