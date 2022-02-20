<template>
  <div>
    Team
    <v-card style="padding: 10px; border-radius: 20px; background: #EAECFC ">
      <TeamSection/>
    </v-card>
  </div>
</template>

<script>
import TeamSection from '../components/TeamSection.vue'

export default {
  name: 'Team',

  components: {
    TeamSection
  }
}
</script>
