<template>
  <footer class="font-grey">
      <div id="upper-footer">
            <div class="container d-flex">
                <div class="col-3">
                    <h2 class="py-10"><span class="brand-color brand-bg-secondary">NEX</span> GEN</h2>
                    <p class="py-10">A functional HTML template for corporate &amp; business</p>
                    <div class="tel">
                        <i class="fas fa-phone-alt"></i>
                        <span>+1(305) 345 6789</span>
                    </div>
                    <div class="mail">
                        <i class="fas fa-envelope"></i>
                        <span>hello@exemple.com</span>
                    </div>
                    <div class="address">
                        <i class="fas fa-map-marker-alt"></i>
                        <span>Main Avenue, 987</span>
                    </div>
                    <Button class="btn-brand" text="get in touch" />
                </div>
                <div class="col-3">
                    <LinkCard title="About" :links="about"/>
                </div>
                <div class="col-3">
                    <LinkCard title="Services" :links="services"/>
                </div>
                <div class="col-3">
                    <LinkCard title="Support" :links="support"/>
                </div>
            </div>
        </div> 
      <div id="bottom-footer">
          <div class="container d-flex font-grey">
              <div>Enjoy the low price. We are tracking any intention of privacy</div>
              <div>
                  <i class="far fa-copyright"></i> 2020 NEXGEN is Proudly Powered by 
                  <a class="brand-color" href="#">Codings.</a>
               </div>
          </div>
      </div>
  </footer>
</template>

<script>
import Button from './Button.vue'
import LinkCard from './LinkCard.vue'
export default {
name: 'Footer',
components: {
    Button,
    LinkCard,
},
data(){
    return {
      about: [
          {
            text: 'The Company',
            url: '#'
          },
          {
            text: 'Institutional',
            url: '#'
          },
          {
            text: 'Social & Events',
            url: '#'
          },
          {
            text: 'Innovation',
            url: '#'
          },
          {
            text: 'Environment',
            url: '#'
          },
          {
            text: 'Technology',
            url: '#'
          },
      ],
            services: [
          {
            text: 'Audit & Assurance',
            url: '#'
          },
          {
            text: 'Financial Advisory',
            url: '#'
          },
          {
            text: 'Analytics M&A',
            url: '#'
          },
          {
            text: 'Middle Marketing',
            url: '#'
          },
          {
            text: 'Legal Consulting',
            url: '#'
          },
          {
            text: 'Regulatory Risk',
            url: '#'
          },
      ],
            support: [
          {
            text: 'Responsibility',
            url: '#'
          },
          {
            text: 'Terms of Use',
            url: '#'
          },
          {
            text: 'About Cookies',
            url: '#'
          },
          {
            text: 'Privacy Policy',
            url: '#'
          },
          {
            text: 'Accessibility',
            url: '#'
          },
          {
            text: 'Information',
            url: '#'
          },
      ]  

    }
}
}
</script>

<style scoped lang="scss">

#upper-footer {
   background-image: url(../assets/images/bg-7.jpg);
   background-size: cover;
   padding: 100px 0;
}

.d-flex {
    justify-content: space-between;
}

.col-3 {
    width: calc(25% - 20px);
    min-height: 310px;
}

.tel {
    margin-top: 30px;
}

.fas {
    margin-bottom: 20px;
    margin-right: 10px;
}

#bottom-footer {
    background-color: #060a0c;
    padding: 30px 0;
}
</style>