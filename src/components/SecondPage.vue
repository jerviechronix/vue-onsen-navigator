<template>
  <ons-page>
    <v-ons-toolbar>
      <div class="left">
        <v-ons-back-button>Page 1</v-ons-back-button>
      </div>
      <div class="center">Page 2</div>
    </v-ons-toolbar>
    <p style="text-align: center">This is the second page</p>
    <p style="text-align: center">
      <v-ons-button @click="push">Push Page 3</v-ons-button>
    </p>

  </ons-page>
</template>





<script>

  import page3 from './ThirdPage.vue';
  
  export default {
    key: 'page2',
  template: '#page2',
  methods: {
    push() {
      this.$emit('push-page', page3);
    }
  }
  };
</script>

<style>
</style>
