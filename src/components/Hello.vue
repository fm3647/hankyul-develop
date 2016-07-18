<template>
  <div class="hello">
    <h1 class="uk-h1">{{ msg }}<span> <i class="uk-icon-train"></i> Sass</span></h1>
  </div>
  <ul class="uk-tab" data-uk-tab>
      <li class="uk-active"><a href="">23234</a></li>
      <li><a href="">Test 작업실시</a></li>
      <li><a href="">.asdfasdf.</a></li>
      <li class="uk-disabled"><a href="">.asdfasdfsf</a></li>
  </ul>
  <div class="uk-margin-top uk-margin-bottom uk-panel uk-panel-box">
    http://www.abc.com/<input type="text" name="name" value="">
  </div>
  <button class="uk-button" data-uk-tooltip title="메시지">ToolTip</button>
</template>
<style>
  .uk-panel-box{color:#999}
  input{background: none;border:none;outline:0}
</style>
<script>
export default {
  data () {
    return {
      // note: changing this line won't causes changes
      // with hot-reload because the reloaded component
      // preserves its current state and we are modifying
      // its initial state.
      msg: 'Hello Component!'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style src="../scss/style.scss" lang="scss" scoped></style>
