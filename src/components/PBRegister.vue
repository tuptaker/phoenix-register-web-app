<template>
  <!-- root node required -->
  <div>
    <!-- your content -->
    <div class="layout-padding">
      <!-- if you want automatic padding -->
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
<template>
  <!-- root node required -->
  <div>
    <!-- your content -->
    <div class="layout-padding">
      <!-- if you want automatic padding -->
            <p class="text-center">Enter your email, desired username, and password below to create an account.</p>
      <p class="text-center">Or tap the 'Login' tab above to login if you already have an account.</p>
      <div class="list">
        <div class="item two-lines">
          <div style="margin-right: 10px;" class="item-label">email:</div>
          <div class="item-content">
            <input placeholder="username" class="full-width">
          </div>
        </div>
        <hr>
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
      <button class="primary full-width">Create Account</button>
    </div>
  </div>
</template>

<style>
</style>
