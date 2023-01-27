<template>
  <div id="app">
    <Title />
    <tasks-box />
  </div>
</template>
<script>
import Title from "./components/Title.vue";
import TasksBox from "./components/TasksBox.vue"

export default {
  components: {
    Title,
    TasksBox
  },
};
</script>
<style>
#app {
  width: 100%;
  height: 100%;
  min-height: 100vh;
  background: linear-gradient(180deg, #42b883 0, #35495e);
  color: white;
  display: flex;
  flex-direction: column;
  align-items: center;
}
</style>
