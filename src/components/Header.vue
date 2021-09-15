<template>
  <header>
    <address id="upper-header">
      <div class="container">
        <i class="fas fa-clock"></i><span>Open hours-Mon-Sat-9-18</span>
      </div>
      <div class="container">
        <i class="fas fa-phone-alt"></i><span>+(1306) 1234 5678</span>
        <i class="fas fa-envelope"></i><span>hello@example.com</span>
        <i class="fab fa-facebook-f"></i>
        <i class="fab fa-twitter"></i>
        <i class="fab fa-linkedin-in"></i>
      </div>
    </address>
    <div id="bottom-header"></div>
  </header>
</template>

<script>
export default {
name: 'Header',
}
</script>

<style scoped lang="scss">
  header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    color: #fff;
  }
  #upper-header {
    background-color: #21333e;
    font-size: 0.5rem;
    font-style: normal;
    display: flex;
    justify-content: space-between;
      * {
        padding: 5px 10px;
      }
  }
</style>