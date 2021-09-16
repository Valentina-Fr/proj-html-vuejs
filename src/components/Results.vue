<template>
  <section class="container text-center">
      <h5 class="brand-color">WHAT ARE WE DOING</h5>
      <h2><span class="brand-bg">Results</span> in Numbers</h2>
      <ul class="d-flex">
          <li>
              <div class="brand-color">128</div>
              <div>Certifications</div>
          </li>
          <li>
              <div class="brand-color">230</div>
              <div>Employees</div>
          </li>
          <li>
              <div class="brand-color">517</div>
              <div>Customers</div>
          </li>
          <li>
              <div class="brand-color">98</div>
              <div>Countries served</div>
          </li>
      </ul>
  </section>
</template>

<script>
export default {
name: 'Results'
}
</script>

<style scoped lang="scss">
section {
    height: 300px;
    background-image: url('../assets/images/bg-1.jpg');
    background-size: cover;
    background-position: center;
    color: #fff;
}

h5 {
    padding-top: 40px;
    padding-bottom: 20px;
}

h2 {
    padding-bottom: 40px 0;
}

ul {
    margin-top: 40px;
    justify-content: center;
    li {
        padding: 25px;
    }
}

li .brand-color {
    font-size: 1.5rem;
    font-weight: 600;
}
</style>