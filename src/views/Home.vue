<template>
  <div>
    <v-card style="padding: 10px; border-radius: 20px; background: #EAECFC ">
      <HomeSectionFirst/>
    </v-card>
  </div>
</template>

<script>
import HomeSectionFirst from '../components/HomeSectionFirst'

export default {
  name: 'Home',

  components: {
    HomeSectionFirst
  }
}
</script>
