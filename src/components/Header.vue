<template>
  <header>
    <address id="upper-header">
      <div>
        <i class="fas fa-clock pe-5"></i><span>Open hours-Mon-Sat-9-18</span>
      </div>
      <div>
        <i class="fas fa-phone-alt pe-5"></i><span class="pe-15">+(1306) 1234 5678</span>
        <i class="fas fa-envelope pe-5"></i><span class="pe-15">hello@example.com</span>
        <i class="fab fa-facebook-f pe-15"></i>
        <i class="fab fa-twitter pe-15"></i>
        <i class="fab fa-linkedin-in"></i>
      </div>
    </address>
    <div id="bottom-header">
      <h1><span class="brand-color">NEX</span>GEN</h1>
    </div>
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
    padding: 5px 50px;
  }
  #bottom-header {
    display: flex;
    justify-content: space-between;
    padding: 5px 50px;
  }
 
</style>