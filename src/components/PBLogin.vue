<template>
  <!-- root node required -->
  <div>
    <!-- your content -->
    <div class="layout-padding">
      <!-- if you want automatic padding -->
      <p class="text-center">Enter your username and password below to login</p>
      <p class="text-center">Or tap the 'Register' tab above to create an account if you don't already have one.</p>
      <div class="list">
        <div class="item two-lines">
          <div class="item-content">
            <input placeholder="username" class="full-width">
          </div>
        </div>
        <hr>
        <div class="item two-lines">
          <div class="item-content">
            <input placeholder="password" class="full-width">
          </div>
        </div>
      </div>
      <button class="primary full-width">Login</button>
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
