<template>
  <ons-page>
    <v-ons-toolbar>
      <div class="left">
        <v-ons-back-button>Page 2</v-ons-back-button>
      </div>
      <div class="center">Page 3</div>
    </v-ons-toolbar>
    <p style="text-align: center">This is the third page</p>
  

  </ons-page>
</template>





<script>

  // import page2 from './SecondPage.vue';
  
  export default {
    key: 'page3',
  template: '#page3',
  // methods: {
  //   push() {
  //     this.$emit('push-page', page2);
  //   }
  // }
  };
</script>

<style>
</style>
