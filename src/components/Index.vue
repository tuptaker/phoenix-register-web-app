<template>
  <q-layout>
    <div slot="header" class="toolbar">
      <q-toolbar-title :padding="0">
        Phoenix Point Buddy
      </q-toolbar-title>
    </div>
    <div class="layout-view">
      <q-tabs :refs="$refs" default-tab="login-tab">
        <q-tab name="login-tab">
          Login
        </q-tab>
        <q-tab name="register-tab">
          Register
        </q-tab>
      </q-tabs>
      <div ref="login-tab"><pb-login></pb-login></div>
      <div ref="register-tab"><pb-register></pb-register></div>
    </div>
  </q-layout>
</template>

<script>
import pblogin from './PBLogin.vue'
import pbregister from './PBRegister.vue'

export default {
  components: {
    'pb-login': pblogin,
    'pb-register': pbregister
  }
}
</script>

<style lang="styl">
.logo-container
  width 192px
  height 268px
  perspective 800px
  position absolute
  top 50%
  left 50%
  transform translateX(-50%) translateY(-50%)
.logo
  position absolute
  transform-style preserve-3d
</style>
