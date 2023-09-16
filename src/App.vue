<template>
  <div>
    导航栏 |
    <router-link to="/">PCK</router-link> |
    <router-link to="/2">PPCCKK</router-link>
  </div>
  <hr />
  <router-view />
</template>

<script>
export default {
  name: 'App'
}
</script>
