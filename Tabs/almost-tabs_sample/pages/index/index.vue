<template>
  <view class="home">
  </view>
</template>

<script>
  import AlmostTab from '@/components/almost-tabs/almost-tab.vue'
  import AlmostTabs from '@/components/almost-tabs/almost-tabs.vue'
  export default {
    name: 'Home',
    components: {
      AlmostTab,
      AlmostTabs
    },
    data () {
      return {
        weightArr: []
      }
    },
    methods: {
    },
    onLoad () {
    }
  }
</script>

<style lang="scss" scoped>
</style>
