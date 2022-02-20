<template>
  <div>
    <div style="padding: 10px 0px 10px 20px">
      <h3>Good Morning Greece</h3>
      <h6 style="color: #535C70">My IP Address 141.101.98.245</h6>
    </div>
    <v-divider></v-divider>
    <div>
     <h3 class="titlestyle">Dashboard</h3>
     <v-row>
      <v-col lg="3">
        <v-card
          class="mx-auto FourCards"
          max-width="344"
        >
          <v-row>
            <v-col lg="4">
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
        >
          <v-row>
            <v-col lg="3">
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
          class="mx-auto FourCards"
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
        class="mx-auto FourCards watchcard"
            max-width="344"
        >
        <v-card-title>
          ROI
        </v-card-title>
        <v-img
          src="../assets/Home/watch.png"
          height="200px"
          width="200px"
          class="ImgTwo"
        ></v-img>
        </v-card>
      </v-col>
      <v-col lg="9">
        <v-card
          style="background: #DBDCF0 "
        >
        <v-row>
          <v-col lg="4">
            <v-row>
              <v-col lg="12">
                <v-card
                  class="mx-auto FourCards"
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
                  class="mx-auto FourCards"
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
        </v-card>
      </v-col>
    </v-row>
  </div>
  </div>
</template>

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
  text-align:center;
  color: #FFFFFF;
  background: transparent linear-gradient(180deg, #4D24F3 0%, #7F08F6 100%)
}
</style>
