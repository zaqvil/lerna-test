<!--
 * @Author: zaqvil
 * @Date: 2021-08-10 20:43:28
 * @FilePath: \lerna\packages\vue\src\App.vue
 * @LastEditTime: 2021-08-10 20:52:23
 * @LastEditors: zaqvil
-->
<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3 + Vite" />
  {{ a }}
  <DAS />
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue'
import common from '@zvil/common'
import DAS from '@zvil/common/a.vue'
import {ref} from 'vue'
const a = ref(common)
// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/master/active-rfcs/0040-script-setup.md
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
