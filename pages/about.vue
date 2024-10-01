<template>

    <div>
      <div class="py-4 bg-warning">
        <div class="container text-center">
          <h3> Giới Thiệu</h3>
        </div>
      </div>
      <Aboutus/>
    </div>
  </template>
  
  <script>
   import Aboutus from '~/components/Aboutus.vue';

   export default {
    name: 'about',
    components: { Aboutus},
    head() {
      return {
        title: 'Giới Thiệu',
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: "B2 - AboutUs"
          },
          {
            hid: 'keywords',
            name: 'keywords',
            content: 'Vue, Nuxt, Javascript - AboutUs'
          }
        ]
      }
    }
   }
  </script>
  
  
  