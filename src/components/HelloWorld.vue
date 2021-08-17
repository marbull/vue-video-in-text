<template>
  <div class="container">
    <video autoplay loop muted>
      <source src="../assets/video-min.mp4" type="video/mp4" />
    </video>
    <div class="text-box">
      <h1>HELLO WORLD</h1>
    </div>
  </div>
</template>

<style scoped>
  .container {
    width: 100%;
    height: 100vh;
    position: relative;
  }
  .container video {
    width: 100%;
    height: 100%;
  }
  .text-box {
    position: absolute;
    top: 0;
    left: 0;
    background: #000;
    width: 100%;
    height: 100%;
    color: #fff;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 100px;
    font-weight: 900;
    mix-blend-mode: multiply;
  }
</style>
