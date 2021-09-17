<template>
  <section class="container-sm text-center">
    <h5 class="brand-color">INTRODUCTION VIDEO</h5>
    <h2>Advisory <span class="brand-bg-secondary brand-color">Performance</span></h2>
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
section {
    margin-bottom: 20px;
}

h5 {
    margin-top: 20px;
}

h2 {
    margin: 10px 0;
}

p {
    margin: 10px 0;
}

img {
    width: 80%;
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