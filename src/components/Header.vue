<template>
  <div class="header">
    <h1 class="uk-h1">{{ msg }}<span> <i class="uk-icon-train"></i> Sass</span></h1>
  </div>
  <ul class="uk-tab" data-uk-tab>
      <li class="uk-active"><a href="">23234</a></li>
      <li><a href="">234234234</a></li>
      <li><a href="">.asdfasdf.</a></li>
      <li class="uk-disabled"><a href="">.asdfasdfsf</a></li>
  </ul>
</template>

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
