<template>
  <v-content>
    <div class="text-center my-12">
      <span class="font-weight-black" style="font-size: 3em; font-family: 'Amatic SC', cursive;"><u>We are giving a bag of your choice from our list</u></span><br/>
      <span class="font-weight-light">when you donate or sponsor the printing of our Christian magazine ( Buddies of Christ-Tropa ni Cristo )</span><br/>
      <span class="font-weight-light">Minimum donation is  $1500.00 to be eligible for the gift.</span>
    </div>
    <v-row>
      <v-col md="6" sm="12">
        <v-carousel style="border: grey 2px solid">
          <v-carousel-item
                  v-for="(item,i) in items"
                  :key="i"
                  :src="item"
                  reverse-transition="fade-transition"
                  transition="fade-transition"
          ></v-carousel-item>
        </v-carousel>
      </v-col>
      <v-col md="6" sm="12">
        <v-card class="pa-5">
          <v-container>
            <v-row>
              <v-col col="12" sm="12">
                <span class="font-weight-black">Sole Propretorship Registration Number: </span>
              </v-col>
              <v-col col="12" sm="12">
                <span class="font-weight-light">FM0728978</span>
              </v-col>
              <v-col col="12" sm="12">
                <span class="font-weight-black">Name of Sole Proprietorship: </span>
              </v-col>
              <v-col col="12" sm="12">
                <span class="font-weight-light">Youth For Truth</span>
              </v-col>
              <v-col col="12" sm="12">
                <span class="font-weight-black">Registration Date: </span>
              </v-col>
              <v-col col="12" sm="12">
                <span class="font-weight-light">September 21, 2017</span>
              </v-col>
              <v-col col="12" sm="12">
                <span class="font-weight-black">Business Start Date: </span>
              </v-col>
              <v-col col="12" sm="12">
                <span class="font-weight-light">Jan 01, 2018</span>
              </v-col>
              <v-col col="12" sm="12">
                <span class="font-weight-black">Business Address: </span>
              </v-col>
              <v-col col="12" sm="12">
                <span class="font-weight-light">603 - 17th 17th ST W NORTH VANCOUVER BC V7M 1V5</span>
              </v-col>
              <v-col col="12" sm="12">
                <span class="font-weight-black">Bank Account: </span>
              </v-col>
              <v-col col="12" sm="12">
                <span class="font-weight-light">525 138 4 (Checking Account)</span>
              </v-col>
              <v-col col="12" sm="12">
                <span class="font-weight-black">Facebook Page: </span>
              </v-col>
              <v-col col="12" sm="12">
                <a href="https://www.facebook.com/bagswithamission/" target="_blank">
                  <span>https://www.facebook.com/bagswithamission/</span>
                </a>
              </v-col>
            </v-row>
          </v-container>
        </v-card>
      </v-col>
    </v-row>
  </v-content>
</template>
<script>
    export default {
        data () {
            return {
                items: [
                    'https://bagswithamission.s3.amazonaws.com/Birkin10%5B1111%5D.jpg',
                    'https://bagswithamission.s3.amazonaws.com/bag+cause2%5B1113%5D.jpg',
                    'https://bagswithamission.s3.amazonaws.com/Bags+w+Cause%5B1114%5D.jpg'
                ]
            }
        },
    }
</script>
