<template>
  <div class="hello">
    <div class="demo">Hello Vue</div>
  </div>
</template>

<script type="text/ecmascript-6">
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
  .hello
    display inline-block
    width 100%
    height 200px
    background antiquewhite
    .demo
      width 200px
      height 200px
      margin auto
      text-align center
      font-size 40px
      font-weight 700
      line-height 200px
      background aqua
</style>
