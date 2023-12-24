<template>
    <footer class="footer" style="background-color: #011e5b;">

        <section class="section  section-components" style="background-color: #003c82; padding: 0.3rem 0;">
            <div class="container" style="font-size: small;">
                <div class="row">
                    <div class="col-md-5 p-2">
                        <img v-lazy="'img/assets/icon-skype.svg'">
                         <span style="color: white; font-weight: 900;"> &nbsp; Pelayanan Pelanggan Skype:</span> <span style="color: #be8a35;font-weight: 700;">&nbsp;affiliasi.id@oleintl.com</span>
                    </div>
                    <div class="col-md-4 p-2">
                        <img v-lazy="'img/assets/icon-email.svg'">
                        <span style="color: white; font-weight: 900;">&nbsp;Email:</span><span style="color: #be8a35;font-weight: 700;">&nbsp; affiliatebola@ole777- indo.com</span>
                    </div>
                    <div class="col-md-3 p-2">
                        <img v-lazy="'img/assets/icon-whatsapp.svg'">
                        <span style="color: white; font-weight: 900;">&nbsp;Whatsapp:</span><span style="color: #be8a35;font-weight: 700;">&nbsp;+6287807264445</span>  
                    </div>
                </div>
            </div>
        </section>

        <div class="container">
            <div class="row align-items-center justify-content-md-between">
                <div class="row">
                    <div class="col-md-3 p-3">
                        <img v-lazy="'img/assets/logo-chelsea.svg'" class="img-fluid">
                    </div>
                    <div class="col-md-3 p-3">
                        <img v-lazy="'img/assets/logo-pagcor.png'" class="img-fluid">
                    </div>
                    <div class="col-md-3 p-3">
                        <img v-lazy="'img/assets/logo-iom.png'" class="img-fluid">
                    </div>
                    <div class="col-md-3 p-3">
                        <img v-lazy="'img/assets/ole777-white.png'" class="img-fluid">
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
export default {
  name: 'app-footer',
  data() {
    return {
      year: new Date().getFullYear()
    }
  }
};
</script>
<style>
</style>
