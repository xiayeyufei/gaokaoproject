<template>

  <v-app>

    <router-view/>
  </v-app>
</template>

<script>
  import index from './components/index';

  export default {
    name: 'App',

    components: {
      index,
    },

    data: () => ({
      //
    }),
  };
</script>
