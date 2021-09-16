<template>
  <section class="container-sm text-center">
    <h6 class="brand-color">INTRODUCTION VIDEO</h6>
    <h3>Advisory <span class="brand-bg brand-color">Performance</span></h3>
    <p class="font-grey">Financial executive need to review their strategies, operating models and capabilities so that their areas can generate sound information for better decision making</p>
    <div class="video">
        <img src="@/assets/images/video-1.jpg" alt="video">
        <i class="fas fa-play"></i>
    </div>
  </section>
</template>

<script>
export default {
name: 'Advisory'
}
</script>

<style scoped lang="scss">
h6 {
    margin-top: 20px;
}

h3 {
    margin: 10px 0;
}

p {
    margin: 10px 0;
}

img {
    width: 80%;
    margin-bottom: 20px;
}

.video {
    position: relative;
}

.fa-play {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    font-size: 30px;
}
</style>