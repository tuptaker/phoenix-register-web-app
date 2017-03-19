<template>
  <!-- root node required -->
  <div>
    <!-- your content -->
    <div class="layout-padding">
      <!-- if you want automatic padding -->
      <div class="list">
        <div class="item two-lines">
          <div style="margin-right: 10px;" class="item-label">username:</div>
          <div class="item-content">
            <input placeholder="username" class="full-width">
          </div>
        </div>
        <hr>
        <div class="item two-lines">
          <div style="margin-right: 10px;" class="item-label">password:</div>
          <div class="item-content">
            <input placeholder="password" class="full-width">
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    data () {
      return {}
    }
  }

</script>

<style>


</style>
