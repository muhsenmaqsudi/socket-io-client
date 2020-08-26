<template>
  <Telegram />
</template>

<script lang="ts">
import Vue from "vue";
import Telegram from "@/components/Telegram.vue"; // @ is an alias to /src

export default Vue.extend({
  name: "Home",
  components: {
    Telegram,
  },
});
</script>
