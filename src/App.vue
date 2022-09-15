<template>
  <div id="app">
    <message>Hello There</message>
    <message>Hello There again</message>
    <message>Hello There again again</message>
  </div>
</template>

<script>
import Message from "./components/Message.vue";

export default {
  name: "app",
  components: { Message },

  data() {
    return {};
  }
};
</script>

<style></style>
