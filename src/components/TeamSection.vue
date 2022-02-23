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
    <v-col lg="8">
   <v-container class="grey lighten-5">
    <v-row>
      <v-col lg="3">
         <v-img
          src="../assets/Team/active12.png"
          height="40px"
          width="180px"
        ></v-img>
      </v-col>
      <v-col lg="3">
         <v-img
          src="../assets/Team/inactive12.png"
          height="40px"
          width="180px"
        ></v-img>
      </v-col>
      <v-col lg="3">
         <v-img
          src="../assets/Team/absent12.png"
          height="40px"
          width="180px"
        ></v-img>
      </v-col>
      <v-col lg="3">
         <v-img
          src="../assets/Team/block.png"
          height="40px"
          width="180px"
        ></v-img>
      </v-col>
    </v-row>
  </v-container>
  </v-col>
  </v-row>
  <v-row>
    <v-col align="center">
        <v-card height="100px" width="100px" class="rootcard">
          <v-img
          src="../assets/Team/user.png"
          height="97px"
          width="97px"
        ></v-img>
        </v-card>
    </v-col>
  </v-row>
  <v-row>
    <v-col align="center" lg="4">
        <v-img
          src="../assets/Team/Group12.png"
          height="60px"
          width="220px"
          style="margin: 0px 0px 0px 200px;"
        ></v-img>
    </v-col>
    <v-col align="center" lg="4">
      <div
          style="height: 25px; width: 1px; background: #C8C6C6"
        >
      </div>
        <div
          style="height: 1px; width: 270px; margin: 0px 0px 0px 30px; background: #C8C6C6"
        >

        </div>
    </v-col>
    <v-col align="center" lg="4">
        <v-img
          src="../assets/Team/active12.png"
          height="50px"
          width="210px"
          style="margin: 0px 0px 0px -200px;"
        ></v-img>
    </v-col>
  </v-row>
<v-row style="margin-top: -50px">
    <v-col align="center" lg="6">
        <div
          class="steptwocard"
          style="height: 50px; width:1px"
        >
        </div>
        <div
          class="steptwocard"
          style="height: 50px; width:50%"
        >

        </div>
    </v-col>
    <v-col align="center" lg="6">
          <div
          class="steptwocard"
          style="height: 50px; width:1px;"
        >
        </div>
        <div
          class="steptwocard"
          style="height: 50px; width:50%;"
        >

        </div>
    </v-col>
  </v-row>
  <v-row style="margin-top: -50px">
    <v-col align="center" lg="3">
        <v-img
          src="../assets/Team/active_green@2x.png"
          height="100px"
          width="100px"
        ></v-img>
    </v-col>
    <v-col align="center" lg="3">
        <v-img
          src="../assets/Team/inactive.png"
          height="100px"
          width="100px"
        ></v-img>
    </v-col>
    <v-col align="center" lg="3">
        <v-img
          src="../assets/Team/absent@2x.png"
          height="100px"
          width="100px"
        ></v-img>
    </v-col>
    <v-col align="center" lg="3">
        <v-img
          src="../assets/Team/block12.png"
          height="100px"
          width="100px"
        ></v-img>
    </v-col>
    <!---------------------------------------------------------->
    <v-col align="center" lg="3"  style="margin-top: -50px">
      <div
          class="steptwocard"
          style="height: 50px; width:1px;"
        >
        </div>
        <div
          class="steptwocard"
          style="height: 50px; width:50%;"
        >
        </div>
    </v-col>
    <v-col align="center" lg="3"  style="margin-top: -50px">
      <div
          class="steptwocard"
          style="height: 50px; width:1px;"
        >
        </div>
        <div
          class="steptwocard"
          style="height: 50px; width:50%;"
        >
        </div>
    </v-col>
    <v-col align="center" lg="3"  style="margin-top: -50px">
      <div
          class="steptwocard"
          style="height: 50px; width:1px;"
        >
        </div>
        <div
          class="steptwocard"
          style="height: 50px; width:50%;"
        >
        </div>
    </v-col>
    <v-col align="center" lg="3"  style="margin-top: -50px">
      <div
          class="steptwocard"
          style="height: 50px; width:1px;"
        >
        </div>
        <div
          class="steptwocard"
          style="height: 50px; width:50%;"
        >
        </div>
    </v-col>
    <v-col align="center" lg="3" style="margin-top: -50px">
      <v-row>
        <v-col>
          <div
          src="../assets/Team/purple113.png"
          style="border: 2px solid purple;"
          class="stepthreecard"
        ></div>
        </v-col>
        <v-col>
          <div
          src="../assets/Team/purple113.png"
          style="border: 2px solid green;"
          class="stepthreecard"
        ></div>
        </v-col>
      </v-row>

    </v-col>
    <!-- <v-col lg="3">

    </v-col> -->
    <v-col align="center" lg="3" style="margin-top: -50px">
      <v-row>
        <v-col>
          <div
          src="../assets/Team/purple113.png"
          style="border: 2px solid orange;"
          class="stepthreecard"
        ></div>
        </v-col>
        <v-col>
          <div
          src="../assets/Team/purple113.png"
          style="border: 2px solid orange;"
          class="stepthreecard"
        ></div>
        </v-col>
      </v-row>
    </v-col>
    <!-- <v-col lg="3">

    </v-col> -->
    <v-col align="center" lg="3" style="margin-top: -50px">
      <v-row>
        <v-col>
          <div
          src="../assets/Team/purple113.png"
          style="border: 2px solid orange;"
          class="stepthreecard"
        ></div>
        </v-col>
        <v-col>
          <div
          src="../assets/Team/purple113.png"
          style="border: 2px solid orange;"
          class="stepthreecard"
        ></div>
        </v-col>
      </v-row>
    </v-col>
    <!-- <v-col lg="3">

    </v-col> -->
    <v-col align="center" lg="3" style="margin-top: -50px">
      <v-row>
        <v-col>
          <div
          src="../assets/Team/purple113.png"
          style="border: 2px solid #1A1A40;"
          class="stepthreecard"
        ></div>
        </v-col>
        <v-col>
          <div
          src="../assets/Team/purple113.png"
          style="border: 2px solid #1A1A40;"
          class="stepthreecard"
        ></div>
        </v-col>
      </v-row>
    </v-col>
  </v-row>
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
  background: greenyellow;
}
.steptwocard {
  border-top:    1px solid  #000;
  border-right:  1px solid #000;
  border-left:   1px solid  #000;
  border-radius: 20px
}
.stepthreecard {
  height:50px;
  width: 100px;
  border-radius: 20px;
  background: #FFFFFF;
}
</style>
