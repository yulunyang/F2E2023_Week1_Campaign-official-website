<template>
  <div id="home">
    <fullPage :options="state.options">
      <div class="section">
        <Section1 />
      </div>
      <div class="section">
        <Section2 />
      </div>
      <div class="section">
        <Section3 />
      </div>
      <div class="section">
        <Section4 />
      </div>
      <div class="section">
        <Section5 />
      </div>
      <div class="section">
        <Section6 />
        <FooterSection />
      </div>
    </fullPage>
  </div>
</template>

<script>
import { reactive } from 'vue'
import Section1 from '@/components/modules/section_1.vue'
import Section2 from '@/components/modules/section_2.vue'
import Section3 from '@/components/modules/section_3.vue'
import Section4 from '@/components/modules/section_4.vue'
import Section5 from '@/components/modules/section_5.vue'
import Section6 from '@/components/modules/section_6.vue'
import FooterSection from '@/components/modules/footerSection.vue'
  export default {
    components: {
      Section1,
      Section2,
      Section3,
      Section4,
      Section5,
      Section6,
      FooterSection
    },
    setup () {
      const state = reactive({
      options: {
          menu: '#menu',
          anchors: ['page1', 'page2', 'page3', 'page4', 'page5', 'page6']
          }
      })
      return {
        state
      }
    },
  };
</script>

<style lang="scss">
  #home {
    margin-top: 70px;
    overflow: hidden;
  }
</style>
