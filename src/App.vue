<template>
  <div id="app">
    <m-header></m-header>
    <tab></tab>
    <keep-alive>
      <router-view/>
    </keep-alive>
    <player></player>
  </div>
</template>

<script>
import Player from "components/player/player";
import MHeader from "components/m-header/m-header";
import Tab from "components/tab/tab";
export default {
  components: {
    MHeader,
    Tab,
    Player
  }
};
</script>

<style>
</style>
