<template>
  <v-app>
   
    <v-content>
      <Promodoro />
    </v-content>
  </v-app>
</template>

<script>
import Promodoro from './components/Promodoro';

export default {
  name: 'App',

  components: {
    Promodoro,
  },

  data: () => ({
    //
  }),
};
</script>
