<template>
  <div>Vue3 + Typescript + Vuex + Vue-Router Test</div>
  <div class="home-page">
    <router-link to="/peoples">Peoples</router-link> |
    <router-link to="/favorites">Favorites</router-link>
  </div>
</template>

<style scoped>
.home-page {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  gap: 16px;
  font-size: 1em;
  padding: 12px;
}
</style>
