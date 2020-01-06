<template lang='pug'>
body
  header.masthead
    .container.h-100
      .row.h-100.align-items-center.justify-content-center.text-center
        .col-lg-10.align-self-end
          h1.text-uppercase.text-white.font-weight-bold Permita que a tecnologia te traga lucro
          hr.divider.my-4
        .col-lg-8.align-self-baseline
          p.text-white-75.font-weight-light.mb-5 blablablabla
          a.btn.btn-primary.btn-xl.js-scroll-trigger(href='#about') Conheça-nos

  // About Section
  section#about.page-section.bg-primary
    .container
      .row.justify-content-center
        .col-lg-8.text-center
          h2.text-white.mt-0 N&oacute;s temos o que voc&ecirc; precisa
          hr.divider.light.my-4
          p.text-white-50.mb-4 blablablablablabla
          a.btn.btn-light.btn-xl.js-scroll-trigger(href='#planos') Veja nossos planos
    
  // contact section
  section#contact.page-section
    .container
      .row.justify-content-center
        .col-lg-8.text-center
          h2.mt-0 Entre em contato!
          hr.divider.my-4
          p.text-muted.mb-5 blablabla!
      .row
        .col-lg-4.ml-auto.text-center.mb-5.mb-lg-0
          i.fas.fa-phone.fa-3x.mb-3.text-muted
          div +55 (84) 99185-6278
        .col-lg-4.mr-auto.text-center
          i.fas.fa-envelope.fa-3x.mb-3.text-muted
          // Make sure to change the email address in anchor text AND the link below!
          a.d-block(href='mailto:help@bot4you.com') help@bot4you.com


</template>

<script>
import marked from '../../tools/marked';
export default {
  data: () => {
    return {
      left
    }
  }
}
</script>

