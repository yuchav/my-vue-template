<template>
  <div>
    <div class="header-mod">header</div>
    <div class="placeholder-mod"></div>
  </div>
</template>

<script>
export default {
  name: 'vheader',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header-mod{
  background:#333;
  position: fixed;
  left:0;
  top:0;
  right:0;
  line-height:40px;
  color:#fff;
  text-align:center;
}
.header-mod+.placeholder-mod{
  height:40px;
}
</style>
