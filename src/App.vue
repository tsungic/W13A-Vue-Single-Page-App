<template>
  <div>
    <layout-header></layout-header>
    <layout-content></layout-content>
    <layout-footer></layout-footer>
  </div>
</template>


<script>
import LayoutHeader from './components/LayoutHeader.vue';
import LayoutContent from './components/LayoutContent.vue';
import LayoutFooter from './components/LayoutFooter.vue';




  export default {
    name:'App',
    components: {
      LayoutHeader,
      LayoutContent,
      LayoutFooter,
    },


    data() {
      return {
      }
    }
  }
</script>



<style>;

</style>
