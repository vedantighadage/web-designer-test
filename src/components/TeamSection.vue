<template>
  <div>
    <v-tabs background-color= "#EAECFC">
    <v-tab>Tree</v-tab>
    <v-tab>Left structure</v-tab>
    <v-tab>Right structure</v-tab>
    <v-tab>Direct referrals</v-tab>
  </v-tabs>
  <v-row>
    <v-col class="titlestyle" lg="3">
      <h3>Tree</h3>
    </v-col>
    <v-col lg="3">

    </v-col>
    <v-col lg="3">

    </v-col>
    <v-col lg="3">
      <v-text-field
        label="Search"
        placeholder="Placeholder"
        outlined
        append-icon="mdi-search"
        style="border-radius: 20px;"
      ></v-text-field>
    </v-col>
  </v-row>
  <v-row>
    <v-col lg="6">
   <v-container class="grey lighten-5">
    <v-row>
      <v-col lg="3">
         <v-img
          src="../assets/Team/active.svg"
          height="30px"
          width="200px"
          :justify="center"
        ></v-img>
      </v-col>
      <v-col lg="3">
         <v-img
          src="../assets/Team/inactive.svg"
          height="30px"
          width="150px"
          :justify="center"
        ></v-img>
      </v-col>
      <v-col lg="3">
         <v-img
          src="../assets/Team/absent.svg"
          height="30px"
          width="200px"
          :justify="center"
        ></v-img>
      </v-col>
      <v-col lg="3">
         <v-img
          src="../assets/Team/block.svg"
          height="30px"
          width="200px"
          :justify="center"
        ></v-img>
      </v-col>
    </v-row>
  </v-container>
  </v-col>
  </v-row>
  <v-row>
    <v-col align="center">
      <v-card height="100px" width="100px" class="rootcard">
        <h1>test</h1>
      </v-card>
    </v-col>
  </v-row>
  <v-row>
    <v-col align="center" lg="6">
      <v-card height="100px" width="100px" class="rootcard">
        <h1>test</h1>
      </v-card>
    </v-col>
    <v-col align="center" lg="6">
      <v-card height="100px" width="100px" class="rootcard">
        <h1>test</h1>
      </v-card>
    </v-col>
  </v-row>
  <v-row>
    <v-col align="center" lg="3">
      <v-card height="100px" width="100px" class="rootcard">
        <h1>test</h1>
      </v-card>
    </v-col>
    <v-col align="center" lg="3">
      <v-card height="100px" width="100px" class="rootcard">
        <h1>test</h1>
      </v-card>
    </v-col>
    <v-col align="center" lg="3">
      <v-card height="100px" width="100px" class="rootcard">
        <h1>test</h1>
      </v-card>
    </v-col>
    <v-col align="center" lg="3">
      <v-card height="100px" width="100px" class="rootcard">
        <h1>test</h1>
      </v-card>
    </v-col>
  </v-row>
  <!-- <v-row>
    <v-col align="center" lg="2">
      <v-card height="50px" width="50px" class="rootcard">
        <h1>test</h1>
      </v-card>
    </v-col>
    <v-col align="center" lg="2">
      <v-card height="50px" width="50px" class="rootcard">
        <h1>test</h1>
      </v-card>
    </v-col>
    <v-col align="center" lg="2">
      <v-card height="50px" width="50px" class="rootcard">
        <h1>test</h1>
      </v-card>
    </v-col>
    <v-col align="center" lg="2">
      <v-card height="50px" width="50px" class="rootcard">
        <h1>test</h1>
      </v-card>
    </v-col>
    <v-col align="center" lg="2">
      <v-card height="50px" width="50px" class="rootcard">
        <h1>test</h1>
      </v-card>
    </v-col>
    <v-col align="center" lg="2">
      <v-card height="50px" width="50px" class="rootcard">
        <h1>test</h1>
      </v-card>
    </v-col>
    <v-col align="center" lg="2">
      <v-card height="50px" width="50px" class="rootcard">
        <h1>test</h1>
      </v-card>
    </v-col>
    <v-col align="center" lg="2">
      <v-card height="50px" width="50px" class="rootcard">
        <h1>test</h1>
      </v-card>
    </v-col>
  </v-row>
   -->
  </div>
</template>

<script>
export default {
  data: () => ({
  })
}
</script>

<style scoped>
.titlestyle{
  padding: 40px 20px 0px 40px;
}
.rootcard{
  border-radius: 50px;
}
</style>
