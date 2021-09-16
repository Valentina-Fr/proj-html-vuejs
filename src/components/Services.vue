<template>
  <section>
      <div class="container">
        <h5 class="brand-color">OUR BUSINESS AREAS</h5>
        <h2>Excellence in <span class="brand-bg">Services</span></h2>
        <div class="d-flex">
            <p class="font-grey">We are leaders in providing consultancy services with a set of cutting-edge technologies and a team of experienced and renowned professionals. These are some options that you can hire.</p>
            <Button class="btn-border" text="See all"/>
        </div>
        <div class="row">
            <div class="col">
                <div class="card">
                    <div class="icons">
                        <i class="fas fa-network-wired brand-color"></i>
                        <i class="fas fa-arrow-right brand-color"></i>
                    </div>
                    <h4 class="text-center">Audit &amp; Assurance</h4>
                    <p class="font-grey">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                </div>
            </div>
            <div class="col">
                <div class="card">
                    <div class="icons">
                        <i class="fas fa-briefcase brand-color"></i>
                        <i class="fas fa-arrow-right brand-color"></i>
                    </div>
                    <h4 class="text-center">Financial Advisory</h4>
                    <p class="font-grey">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                </div>
            </div>
            <div class="col">
                <div class="card">
                    <div class="icons">
                        <i class="fas fa-chart-bar brand-color"></i>
                        <i class="fas fa-arrow-right brand-color"></i>
                    </div>
                    <h4 class="text-center">Analytics and M &amp; A</h4>
                    <p class="font-grey">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                </div>
            </div>
            <div class="col">
                <div class="card">
                    <div class="icons">
                        <i class="fas fa-plane brand-color"></i>
                        <i class="fas fa-arrow-right brand-color"></i>
                    </div>
                    <h4 class="text-center">Middle Marketing</h4>
                    <p class="font-grey">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                </div>
            </div>
            <div class="col">
                <div class="card">
                    <div class="icons">
                        <i class="fas fa-globe brand-color"></i>
                        <i class="fas fa-arrow-right brand-color"></i>
                    </div>
                    <h4 class="text-center">Legal Consulting</h4>
                    <p class="font-grey">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                </div>
            </div>
            <div class="col">
                <div class="card">
                    <div class="icons">
                        <i class="fas fa-inbox brand-color"></i>
                        <i class="fas fa-arrow-right brand-color"></i>
                    </div>
                    <h4 class="text-center">Regulatory Risk</h4>
                    <p class="font-grey">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                </div>
            </div>
        </div>
      </div>
  </section>
</template>

<script>
import Button from './Button.vue'
export default {
name: 'Services',
components: {
    Button
}
}
</script>

<style scoped lang="scss">
section {
    background-color: #111117;
    color: #fff;
}

h5 {
    padding-top: 40px;
    padding-bottom: 20px;
}

h2 {
    padding-bottom: 40px;
}

p {
    padding-right: 250px;
}

.d-flex {
    margin-bottom: 40px;
}

.col {
    width: calc(100% / 3 - 20px);
}
    
.row {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}

.card {
    background-color: #19191f;
    border-radius: 5px;
    padding-top: 20px;
    margin-bottom: 20px;
    .fas {
        font-size: 30px;
        vertical-align: middle;
        padding-left: 20px;
    }

    .fa-arrow-right {
        font-size: 20px;
        padding-right: 20px;
        padding-left: 70%;
    }
    
    h4 {
        padding: 20px 0;
    }
    p {
        padding: 20px 30px;
    }
}
</style>