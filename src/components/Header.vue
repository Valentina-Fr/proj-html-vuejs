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
      <h2><span class="brand-color brand-bg-secondary">NEX</span> GEN</h2>
      <div class="d-flex">
        <ul>
          <li v-for="(link, index) in links" :key="index"><a :href="link.url">{{link.text}}</a></li>
        </ul>
        <a href="#"><img class="download" src="@/assets/images/image (1).png" alt="download"></a>
        <Button class="btn-brand" text="Get in touch"/>
      </div>
    </div>
  </header>
</template>

<script>
import Button from './Button.vue'

export default {
name: 'Header',
components: {
  Button,
},
props: ['links'],
}
</script>

<style scoped lang="scss">
  header {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    color: #fff;
  }
  #upper-header {
    background-color: #21333e;
    font-size: 0.7rem;
    font-style: normal;
    display: flex;
    justify-content: space-between;
    padding: 10px 50px;
  }
  #bottom-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px 50px;
  }
  ul {
    display: flex;
      li a{
        font-size: 0.9rem;
        padding-right: 10px;
        text-transform: uppercase;
      }
  }
  .download {
    vertical-align: middle;
    margin-right: 10px;
  }
  .d-flex {
    align-items: center;
  }

  .btn-brand {
    margin-left: 10px;
  }
 
</style>