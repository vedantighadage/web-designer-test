<template>
  <div>
  <v-row style="margin: 10px">
    <v-col lg="2" md="2">
      <Sidebar/>
  </v-col>
  <v-col lg="10" md="10">
  <div>
    <router-view/>
  </div>
  </v-col>
  </v-row>
  </div>
</template>

<script>
import Sidebar from './components/Sidebar.vue'

export default {
  name: 'App',
  components: {
    Sidebar
  },

  data: () => ({
    //
  })
}
</script>
