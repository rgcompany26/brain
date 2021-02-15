<template>
  <h1>Equation</h1>
  <span>{{ formula }}</span>
</template>

<script>
export default {
  name: "RGEquation",
  props: {
  },
  mounted(){
    if (window.MathJax){
      window.MathJax.typeset();
    }
  },
  data() {
    return {
      formula: '$$x = {-b \\pm \\sqrt{b^2-4ac} \\over 2a}.$$'
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="stylus" scoped>
h3
  margin 40px 0 0

ul
  list-style-type none
  padding 0

li
  display inline-block
  margin 0 10px

a
  color #42b983
</style>
