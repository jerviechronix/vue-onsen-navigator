<template>
  <ons-page>
    <v-ons-toolbar>
      <div class="center">Page 1</div>
    </v-ons-toolbar>
    <p style="text-align: center">
      This is the first page
      <v-ons-button @click="push">Push Page 2</v-ons-button>
    </p>

  </ons-page>
</template>





<script>

  import page2 from './SecondPage.vue';
  
  export default {
    key: 'page1',
  template: '#page1',
  methods: {
    push() {
      this.$emit('push-page', page2);
    }
  }
  };
</script>

<style>
</style>
