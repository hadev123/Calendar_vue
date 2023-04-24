<template>
  <v-app>
    <CalendarTraining />
  </v-app>
</template>

<script>
import CalendarTraining from "./components/CalendarTraining";

export default {
  name: "App",

  components: {
    CalendarTraining,
  },

  data: () => ({
    //
  }),
};
</script>
