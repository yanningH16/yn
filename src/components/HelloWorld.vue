<template>
  <div class="hello">
    <h1>鄢宁简历制作中.....</h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
    }
  },
  methods: {
    ceshi () {
      var arr = [1, 5, 1, 7, 5, 9]
      console.log(Math.max(...arr))
      console.log([...new Set([2, 2, 12, 1, 2, 1, 6, 12, 13, 6])])
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="stylus" rel="stylesheet/stylus" scoped>
h1, h2
  font-weight normal
ul
  list-style-type none
  padding 0
li
  display inline-block
  margin 0 10px
a
  color #42b983
.text
  width 100px
  display -webkit-box
  -webkit-box-orient vertical
  -webkit-line-clamp 3
  overflow hidden
</style>
