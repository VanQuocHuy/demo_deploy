<template>
    <div class="container">
      <div class="py-4 bg-warning">
        <div class="container text-center">
          <h3>Liên Hệ</h3>
        </div>
      </div>
      <div class="py-5">
      <div class="container">
        <div class="row">
          <div class="col-md-8">
            <h1 class="main-heading">Nếu bạn có bất kỳ thắc mắc nào</h1>
            <h4>Hãy liên hệ với chúng tôi qua Email: levanquochuy06022001@gmail.com</h4>
          </div>
          <div class="col-md-4 text-center my-auto">
          <NuxtLink to="/contact" class="px-5 py-2 btn btn-primary">Liên hệ với chúng tôi</NuxtLink>
          </div>
        </div>
      </div>
     </div>
    </div>
  </template>
  
  <script>
   export default {
    name: 'contact',
    head() {
      return {
        title: 'Liên Hệ',
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: "B2 - Liên Hệ"
          },
          {
            hid: 'keywords',
            name: 'keywords',
            content: 'Vue, Nuxt, Javascript - Liên Hệ'
          }
        ]
      }
    }
   }
  </script>
  
  
  