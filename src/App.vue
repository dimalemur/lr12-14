<template>
  <div id="app">
    <h1 class="jumbotron text-center">Notebook</h1>
    <Contacts />
  </div>
</template>

<script>
import Сontacts from "./components/contacts.vue";

export default {
  name: "App",
  components: {
    Contacts: Сontacts
  }
};
</script>
