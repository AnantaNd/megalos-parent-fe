<template>
  <v-app>
    <v-main>
      <HelloWorld />
      <div class="flex flex-row justify-center">
        <h1 class="text-red-800 font-bold">helo</h1>
      </div>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
