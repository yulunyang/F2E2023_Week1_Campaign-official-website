<template>
  <div id="main" class="m-0 p-0">
    <HeaderSection />
    <router-view />
    <!-- <FooterSection /> -->
  </div>
</template>
<script>
import HeaderSection from '@/components/modules/headerSection.vue'
// import FooterSection from '@/components/modules/footerSection.vue'
export default ({
  components: {
    HeaderSection
    // FooterSection
  },
  setup () {

  },
})
</script>

<style lang="scss">
#main {
  font-family: 'Noto Sans', sans-serif;
  font-family: 'Noto Sans JP', sans-serif;
  font-family: 'Noto Sans SC', sans-serif;
  font-family: 'Noto Sans TC', sans-serif;
}
</style>
