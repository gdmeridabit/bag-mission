<template>
  <v-content class="background">
    <div class="home-top-video">
      <div class="d-flex flex-column home-text text-center">
        <span style="font-size: 6em; font-family: 'Dosis', sans-serif; ">Bags with a Mission</span>
      </div>
    </div>
  </v-content>
</template>

<script>
    export default {
        data: () => ({
            bgImg: 'https://bagswithamission.s3.amazonaws.com/bg.jpeg'
        }),
    };
</script>

<style>
  @import url('https://fonts.googleapis.com/css?family=Dosis&display=swap');
  @import url('https://fonts.googleapis.com/css?family=Amatic+SC&display=swap');

  @media only screen and (max-width: 768px) {
    /* For mobile phones: */
    .background {
      height: 100vh;
      background: url('https://bagswithamission.s3.amazonaws.com/bg.jpeg') no-repeat center;
    }
  }

  @media only screen and (min-width: 768px) {
    /* For desktop: */
    .background {
      height: 50vh;
      background: url('https://bagswithamission.s3.amazonaws.com/bg.jpeg') no-repeat center;
    }
  }

  .home-top-video:before {
    content: "";
    position: absolute;
    top: 0;
    right: 0;
    left: 0;
    bottom: 0;
    z-index: 1;
    background: linear-gradient(
            to right,
            rgba(0, 0, 0, 0.5),
            rgba(99, 50, 110, 0.7)
    );
  }

  .home-top-video {
    left: 0;
    top: 0;
    height: 50vh;
    width: 100%;
    overflow: hidden;
    z-index: -1;
  }

  .home-text {
    position: absolute;
    top: 50%;
    left: 50%;
    -webkit-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
    color: #fff;
    z-index: 10;
  }
</style>
