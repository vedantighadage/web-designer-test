<template>
  <div>
    <div style="padding: 10px 0px 10px 20px">
      <v-card style="float: right; padding:5px"><p>TRX2612571</p>
      <!-- <v-avatar>
      <img
        src="https://cdn.vuetifyjs.com/images/john.jpg"
        alt="John"
        size="36"
      >
    </v-avatar> -->
    </v-card>
      <h3>Good Morning Greece</h3>
      <h6 style="color: #535C70">My IP Address 141.101.98.245</h6>

    </div>
    <v-divider></v-divider>
    <div>
    <h3 class="titlestyle">Dashboard</h3>
      <v-row>
        <v-col lg="3">
          <v-card
            class="mx-auto FourCardsOne"
            max-width="344"
            style= "box-shadow: 8px 8px 18px #04044345"
          >
            <v-row>
              <v-col lg="4" sm="12" xs="12" md="12">
                <v-img
                  src="../assets/Home/roi_income (1).svg"
                  height="40px"
                  width="40px"
                  class="ImgOne"
                ></v-img>
              </v-col>
              <v-col lg="8">
                <v-img
                  src="../assets/Home/roi_income.svg"
                  height="40px"
                  width="100px"
                  class="ImgTwo"
                ></v-img>
              </v-col>
            </v-row>
            <v-card-subtitle>
              ROI Income
            </v-card-subtitle>
            <h4 class="hfourstyle">4280.884 TRX</h4>
          </v-card>
        </v-col>
        <v-col lg="3">
          <v-card
            class="mx-auto FourCards"
            max-width="344"
            style= "box-shadow: 8px 8px 18px #04044345"
          >
            <v-row>
              <v-col lg="4">
                <v-img
                  src="../assets/Home/direct_income.svg"
                  height="40px"
                  width="40px"
                  class="ImgOne"
                ></v-img>
              </v-col>
              <v-col lg="8">
                <v-img
                  src="../assets/Home/direct_income (1).svg"
                  height="40px"
                  width="100px"
                  class="ImgTwo"
                ></v-img>
              </v-col>
            </v-row>
            <v-card-subtitle>
              ROI Income
            </v-card-subtitle>
            <h4 class="hfourstyle">4280.884 TRX</h4>
          </v-card>
        </v-col>
        <v-col lg="3">
          <v-card
            class="mx-auto FourCards"
            max-width="344"
            style= "box-shadow: 8px 8px 18px #04044345"
          >
            <v-row>
              <v-col lg="3" md="6" sm="12" xs="12">
                <v-img
                  src="../assets/Home/binary_income.svg"
                  height="40px"
                  width="40px"
                  class="ImgOne"
                ></v-img>
              </v-col>
              <v-col lg="8">
                <v-img
                  src="../assets/Home/binary_income (1).svg"
                  height="40px"
                  width="100px"
                  class="ImgTwo"
                ></v-img>
              </v-col>
            </v-row>
            <v-card-subtitle>
              ROI Income
            </v-card-subtitle>
            <h4 class="hfourstyle">4280.884 TRX</h4>
          </v-card>
        </v-col>
        <v-col lg="3">
          <v-card
            class="mx-auto FourCardsLast"
            max-width="344"
            style= "box-shadow: 8px 8px 18px #04044345"
          >
            <v-row>
              <v-col lg="4">
                <v-img
                  src="../assets/Home/current_earning_limit.svg"
                  height="40px"
                  width="40px"
                  class="ImgOne"
                ></v-img>
              </v-col>
              <v-col lg="8">
                <v-img
                  src="../assets/Home/current_earning_limit (1).svg"
                  height="40px"
                  width="100px"
                  class="ImgTwo"
                ></v-img>
              </v-col>
            </v-row>
            <v-card-subtitle>
              ROI Income
            </v-card-subtitle>
            <h4 class="hfourstyle">4280.884 TRX</h4>
          </v-card>
        </v-col>
      </v-row>
      <v-row>
        <v-col lg="3">
          <v-card
          class="mx-auto watchcard"
              max-width="344"
          >
          <v-card-subtitle>
            <h2 style="color: white">ROI</h2>
          </v-card-subtitle>

            <v-card-subtitle style="color: white">
              ROI Income
            </v-card-subtitle>
          <v-img
            src="../assets/Home/watch.png"
            height="200px"
            width="200px"
            class="ImgTwo"
          ></v-img>
          <v-card-subtitle style="color: white">
              00 Hours
            </v-card-subtitle>
          </v-card>
        </v-col>
        <v-col lg="9">
          <v-container
            style="background: #DBDCF0 "
          >
          <v-row>
            <v-col lg="4">
              <v-row>
                <v-col lg="12">
                  <v-card
                    class="mx-auto FourCardsTwo"
                    max-width="344"
                  >
                    <v-row>
                      <v-col lg="4">
                        <v-img
                          src="../assets/Home/current_earning_limit.svg"
                          height="40px"
                          width="40px"
                          class="ImgOne"
                        ></v-img>
                      </v-col>
                    </v-row>
                    <v-card-subtitle>
                      ROI Income
                    </v-card-subtitle>
                    <h4 class="hfourstyle">4280.884 TRX</h4>
                  </v-card>
                  <v-card
                    class="mx-auto FourCardsTwo"
                    max-width="344"
                  >
                    <v-row>
                      <v-col lg="4">
                        <v-img
                          src="../assets/Home/current_earning_limit.svg"
                          height="40px"
                          width="40px"
                          class="ImgOne"
                        ></v-img>
                      </v-col>
                    </v-row>
                    <v-card-subtitle>
                      ROI Income
                    </v-card-subtitle>
                    <h4 class="hfourstyle">4280.884 TRX</h4>
                  </v-card>
                </v-col>
                <v-col lg="12">

                </v-col>
              </v-row>
            </v-col>
            <v-col lg="8">
              <v-card-title>
                My Total Earnings
              </v-card-title>
              <v-card-subtitle>
                4471.440 TRX
              </v-card-subtitle>
              <v-img
                src="../assets/Home/my_total_earning.png"
                height="70%"
                width="80%"
                class="ImgTwo"
              ></v-img>
            </v-col>
          </v-row>
          </v-container>
        </v-col>
      </v-row>
      <v-row>
        <v-col lg="6">
          <v-btn depressed
            width="100%"
            class="btnstyle"
          >
            Add Fund
          </v-btn>
        </v-col>
        <v-col lg="6">
          <v-btn depressed
            width="100%"
            color="white"
            class="btnstyle"
          >
            Withdrow
          </v-btn>
        </v-col>
      </v-row>
      <v-row>
        <v-col lg="12">
          <v-card
            class="mt-4 mx-auto"
            max-width="100%"
          >
            <v-sheet
              class="v-sheet--offset mx-auto"
              color="cyan"
              elevation="12"
              max-width="calc(100% - 32px)"
            >
              <v-sparkline
                :labels="labels"
                :value="value"
                color="white"
                line-width="1"
                padding="5"
                style="color: #270082"
              ></v-sparkline>
            </v-sheet>
            <v-sheet
              class="v-sheet--offset mx-auto"
              color="cyan"
              elevation="12"
              max-width="calc(100% - 32px)"
            >
              <v-sparkline
                :labels="labels"
                :value="value"
                color="white"
                line-width="1"
                padding="5"
                style="color: #00B4D8"
              ></v-sparkline>
            </v-sheet>
            <v-sheet
              class="v-sheet--offset mx-auto"
              color="cyan"
              elevation="12"
              max-width="calc(100% - 32px)"
            >
              <v-sparkline
                :labels="labels"
                :value="value"
                color="white"
                line-width="1"
                padding="5"
                style="color: #2EB086"
              ></v-sparkline>
            </v-sheet>
          </v-card>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    value: [
      423,
      446,
      675,
      510,
      590,
      610,
      760
    ]
  })
}
</script>

<style scoped>
.ImgOne{
  margin: 10px 10px 10px 20px;
}
/* .ImgTwo{
  margin: 10px 10px 10px -20px;
} */
.FourCards{
  background: #EFF2FE;
  padding: 0px 0px 20px 0px;
  margin: 40px 5px 20px 5px;
  border-radius: 20px;
}
.FourCardsOne{
  background: #EFF2FE;
  padding: 0px 0px 20px 0px;
  margin: 40px 5px 20px 20px;
  border-radius: 20px;
}
.FourCardsLast{
  background: #EFF2FE;
  padding: 0px 0px 20px 0px;
  margin: 40px 5px 20px 20px;
  border-radius: 20px;
}
.FourCardsTwo{
  background: #EFF2FE;
  padding: 0px 0px 20px 0px;
  margin: 40px 20px 20px 20px;
  border-radius: 20px;
}
.titlestyle{
  margin: 20px 20px 0px 20px;
}
.hfourstyle{
  margin: -10px 0px 0px 15px;
}
.watchcard{
  text-align: -webkit-center;
  /* text-align:center; */
  border-radius: 20px;
  color: #FFFFFF;
  background: transparent linear-gradient(180deg, #4D24F3 0%, #7F08F6 100%);
}
.btnstyle{
  /* text:#FFFFFF; */
  color:aliceblue;
  background: transparent linear-gradient(102deg, #73BBEA 0%, #5654E6 100%)
}
</style>
