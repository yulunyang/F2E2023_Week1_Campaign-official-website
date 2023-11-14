<template>
  <div id="main">
    <Section1 />
    <Section2 />
    <Section3 />
    <Section4 />
    <Section5 />
    <Section6 />
  </div>
</template>

<script>
import Section1 from '@/components/modules/section_1.vue'
import Section2 from '@/components/modules/section_2.vue'
import Section3 from '@/components/modules/section_3.vue'
import Section4 from '@/components/modules/section_4.vue'
import Section5 from '@/components/modules/section_5.vue'
import Section6 from '@/components/modules/section_6.vue'
  export default {
    components: {
      Section1,
      Section2,
      Section3,
      Section4,
      Section5,
      Section6
    },
    setup () {
      return {
      }
    },
  };
</script>

<style lang="scss">
  #main {
    margin-top: 56px;
  }
</style>
