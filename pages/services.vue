<template>
    <div>
      <div class="py-4 bg-warning">
        <div class="container text-center">
          <h3>Dịch Vụ</h3>
        </div>
      </div>
     <OurServices/>
    </div>
  </template>
  
  <script>
   import OurServices from '~/components/OurServices.vue';

   export default {
    name: 'services',
    components: {OurServices},
    head() {
      return {
        title: 'Dịch Vụ',
        meta: [
          {
            hid: 'description', 
            name: 'description',
            content: "B2 - Dịch Vụ"
          },
          {
            hid: 'keywords',
            name: 'keywords',
            content: 'Vue, Nuxt, Javascript - Dịch Vụ'
          }
        ]
      }
    }
   }
  </script>
  
  
  