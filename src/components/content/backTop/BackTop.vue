<template>
  <div class="backtop">
    <img src="~assets/img/common/top.png" alt="">
  </div>
</template>

<script>
export default {
  name: 'BackTop',

  data() {
    return {
      
    };
  },

  mounted() {
    
  },
};
</script>

<style scoped>
.backtop{
  position:fixed;
  z-index: 10;
  bottom: 55px;
  right: 8px;
}
.backtop img{
  width: 44px;
  height: 44px;
}
</style>