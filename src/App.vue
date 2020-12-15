<template lang="pug">
who can say
</template>

<script>
import initHeap from './vendor/heap'

export default {
  mounted() { initHeap(1341481683) }
}
</script>

<style lang="stylus">
@font-face
  font-family 'Harriet Text'
  font-style italic
  font-weight bold
  src local('Harriet Text Bold'), url('/HARRIETTEXTBOLDITALIC.woff') format('woff')

:root
  background-color #fff200
  font italic normal bold 34px/40px 'Harriet Text', serif
  &, body, #app
    height 100%

#app
  align-items center
  display flex
  justify-content center
  margin 0 auto
  max-width 640px
  padding 40px 40px

span
  text-align center
</style>
