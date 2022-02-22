<template>
   <v-card
    height="640"
    width="256"
    class="mx-auto"
    style="border-radius: 20px; box-shadow: 4px 4px 9px #04044345"
  >
    <v-navigation-drawer permanent style="background: #F6F6FF">
      <v-list-item>
        <v-list-item-content>
          <v-list-item-title class="text-h6">
            Demo
          </v-list-item-title>
          <v-list-item-subtitle>
            Panel 05
          </v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>

      <v-divider></v-divider>

      <v-list
        dense
        nav
      >
        <v-list-item
          link
          to="/"
        >
          <v-list-item-icon>
            <v-icon>mdi-home</v-icon>
          </v-list-item-icon>

          <v-list-item-content>
            <v-list-item-title>Home</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
        <v-list-item
          link
          to="/team"
        >
          <v-list-item-icon>
            <v-icon>mdi-account-multiple</v-icon>
          </v-list-item-icon>

          <v-list-item-content>
            <v-list-item-title>Team</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
        <v-list-item
          link
          to="/#"
        >
          <v-list-item-icon>
            <v-icon>mdi-wallet</v-icon>
          </v-list-item-icon>

          <v-list-item-content>
            <v-list-item-title>Invest Wallet</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
        <v-list-item
          link
          to="/#"
        >
          <v-list-item-icon>
            <v-icon>mdi-clipboard-text</v-icon>
          </v-list-item-icon>

          <v-list-item-content>
            <v-list-item-title>Reports</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
        <v-list-item
          link
          to="/#"
        >
          <v-list-item-icon>
            <v-icon>mdi-wallet</v-icon>
          </v-list-item-icon>

          <v-list-item-content>
            <v-list-item-title>Income</v-list-item-title>
          </v-list-item-content>
        </v-list-item><v-list-item
          link
          to="/#"
        >
          <v-list-item-icon>
            <v-icon>mdi-wallet</v-icon>
          </v-list-item-icon>

          <v-list-item-content>
            <v-list-item-title>Withdrawal</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
        <v-list-item
          to="/#"
        >
          <v-list-item-icon>
            <v-icon>mdi-logout</v-icon>
          </v-list-item-icon>

          <v-list-item-content>
            <v-list-item-title>Logout</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list>
      <v-card
      height="120px"
      style="margin: 15px; background: transparent linear-gradient(180deg, #4D24F3 0%, #7F08F6 100%)"
    >

    </v-card>
    <v-card-subtitle>
    <h5>Demo Panel 05 </h5>
    <h6>© 2021 All Rights Reserved</h6>
    </v-card-subtitle>
    </v-navigation-drawer>

  </v-card>
</template>

<style scoped>
.v-list .v-sheet .theme--light .v-list--dense .v-list--nav{
  background: red;
}
</style>
