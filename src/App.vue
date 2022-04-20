<template>
  <div id="app">
    <TaskTimerList/>
  </div>
</template>

<script>
import TaskTimerList from "./components/TaskTimerList";

export default {
  name: "App",
  components: {
    TaskTimerList
  }
};
</script>