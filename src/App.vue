<template>
  <div class="font-poppins">
    <Header />
    <Main />
    <Footer /> 
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Header from '@/components/Header/index.vue'
import Main from '@/components/Main/index.vue'
import Footer from '@/components/Footer/index.vue'
import Modal from '@/components/Modal.vue'

export default defineComponent({
  name: 'App',
  components: {
    Header,
    Main,
    Footer,
  }
});
</script>

<style >

</style>
