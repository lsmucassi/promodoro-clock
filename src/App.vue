<template>
  <v-app>
   
    <v-content>
      <v-container>
        <v-row>
          <v-col sm="6" offset-sm="3">
            <Promodoro />
          </v-col>
        </v-row>
      </v-container>
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
