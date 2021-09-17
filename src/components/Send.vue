<template>
  <section>
      <div class="container d-flex">
        <div class="col-8">
            <h5 class="brand-color">SEND A MESSAGE</h5>
            <h2>Get in <span class="brand-bg-secondary brand-color">Touch</span></h2>
            <p class="font-grey">We will respond to your message as soon as possible</p>
            <div class="form">
                <input type="text" placeholder="Name"> 
                <input type="email" placeholder="E-mail">
                <input type="tel" placeholder="Phone">
                <select id="Info">
                    <option>More info</option>
                </select>
                <textarea id="message" cols="30" rows="10">Message</textarea>
                <Button class="btn-brand" text="Send"/>
            </div>
        </div>
        <div class="col-4">
            <h3>Exemple Inc.</h3>
            <p class="font-grey py-10">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            <p class="font-grey py-10">Consectetur laborum pariatur exercitationem ad cupiditate ex consequuntur aperiam quibusdam possimus a aspernatur, eligendi reprehenderit totam soluta.</p>
            <div class="tel brand-color">
                <i class="fas fa-phone-alt"></i>
                <span>+1(305) 345 6789</span>
            </div>
            <div class="mail brand-color">
                <i class="fas fa-envelope"></i>
                <span>hello@exemple.com</span>
            </div>
            <div class="address brand-color">
                <i class="fas fa-map-marker-alt"></i>
                <span>Main Avenue, 987</span>
            </div>
            <Button class="btn-border" text="view map" />
        </div>
      </div>
  </section>
</template>

<script>
import Button from './Button.vue'
export default {
name: 'Send',
components: {
    Button,
}
}
</script>

<style scoped lang="scss">
.d-flex {
    padding-top: 60px;
    padding-bottom: 60px;
}

h2 {
    padding: 40px 0;
}

.col-8 {
    width: 75%;
}

.col-4 {
    width: 25%;
}

.form {
    margin-top: 20px;
}

input, select {
    width: 43%;
    height: 40px;
    margin-bottom: 20px;
    margin-right: 2%;
    background-color: #ececec;
    color: #757575;
    border: 1px solid transparent;
    border-radius: 3px;
    padding-left: 10px;
}

textarea {
    width: 88%;
    margin-bottom: 20px;
    background-color: #ececec;
    border: 1px solid transparent;
    border-radius: 3px;
    padding-left: 10px; 
    padding-top: 10px;
    display: block;
    font-family: sans-serif;
    color: #757575;
}

.tel {
    margin-top: 30px;
}

.fas {
    padding: 10px;
    border-radius: 50%;
    margin-right: 10px;
    margin-bottom: 30px;
    background-color: rgba(0, 166, 166, 0.2);
}

.fa-map-marker-alt {
    padding: 10px 12px;
}

.btn-border {
    color: #41c457;
}
</style>