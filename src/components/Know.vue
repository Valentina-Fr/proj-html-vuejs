<template>
  <section>
      <div class="container-sm d-flex">
        <div>
            <h5 class="brand-color">NEWSLETTER</h5>
            <h2><span class="brand-bg-secondary brand-color">Know</span> First</h2>
            <p class="font-grey">Follow closely and receive content about our company and the news of the current market.</p>
        </div>
        <div class="form">
            <input type="text" placeholder="Name"> 
            <input type="email" placeholder="E-mail">
            <Button class="btn-brand" text="Subscribe"/>
        </div>
      </div>
  </section>
</template>

<script>
import Button from './Button.vue'
export default {
name: 'Know',
components: {  
    Button,  
}
}
</script>

<style scoped lang="scss">
section {
    background-color: #111117;
    color: #fff;
    padding: 30px 0;
}

.d-flex {
    padding-top: 40px;
    padding-bottom: 20px;
}

h2 {
    padding: 40px 0;
}

.form {
    padding-left: 20px;
}

input {
    width: 80%;
    height: 40px;
    margin-bottom: 20px;
    background-color: #1d1d23;
    color: #bcbdbd;
    border: 1px solid transparent;
    border-radius: 3px;
    padding-left: 10px;
}
</style>