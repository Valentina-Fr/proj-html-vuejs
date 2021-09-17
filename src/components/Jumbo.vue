<template>
  <div class="jumbo">
    <div class="text-center">
      <h1>Financial Risk</h1>
      <p class="font-grey">The right outcomes depend on continuous rigor in governance, models and processes across the finance function.</p>
      <Button class="btn-brand" text="Get in touch"/>
      <Button class="btn-border" text="Read More" />
    </div>
  </div>
</template>

<script>
import Button from './Button.vue'

export default {
name: 'Jumbo',
components: {
  Button
}
}
</script>

<style scoped lang="scss">
  .jumbo {
    background-image: url('../assets/images/bg-2.jpg');
    background-size: cover;
    height: 600px;
    color: #fff;
    display: flex;
    justify-content: center;
    align-items: center;
    div {
      max-width: 50%;
    }
  }
  .btn-brand, .btn-border {
    margin: 0 15px;
  }
  p {
    font-size: 0.9rem;
    padding: 20px 0;
  }
</style>