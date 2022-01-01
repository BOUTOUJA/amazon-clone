<template>
  <div class="home">
    <Header />
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src
import Header from '@/components/Header.vue';

export default defineComponent({
  name: 'Home',
  components: {
    HelloWorld,
    Header,
  },
});
</script>
