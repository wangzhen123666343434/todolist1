<template>
  <div>
    <nav-header></nav-header>
    <nav-main></nav-main>
    <nav-footer></nav-footer>
  </div>
</template>

<script>

import NavHeader from '@/components/navHeader/NavHeader'
import NavMain from '@/components/navMain/NavMain'
import NavFooter from '@/components/navFooter/NavFooter'
import { defineComponent } from 'vue'

export default defineComponent({
  name:"Home",
  // 接受父组件数据
  props:{

  },
  // 定义子组件
  components:{
    NavHeader,
    NavMain,
    NavFooter
  },
  setup(props,ctx) {
    return {

    }
  },
})
</script>
<style lang="scss" scoped>

</style>