<template>
  <v-app>
    <myToolbar />

    <v-content>
      <v-slide-y-transition mode="out-in">
        <router-view />
      </v-slide-y-transition>
    </v-content>
  </v-app>
</template>

<script>
  import myToolbar from "@/components/MyToolbar";
  export default {
    name: "app",
    components: { myToolbar }
  };
</script>
