<template>
    <HelloWorld />
    <div class="manage">
      <h1>Manage</h1>
    </div>
  </template>

<script>
import { defineComponent } from 'vue';

// Components
import HelloWorld from '../components/HelloWorld.vue';

export default defineComponent({
  name: 'HomeView',

  components: {
    HelloWorld,
  },
});
</script>
<style scoped>
.manage {
  background-color: #f5f5f5;
  color: #333;
  text-align: center;
  padding: 20px;
  border: 1px solid #ddd;
  border-radius: 4px; 
}
h1 {
  font-size: 24px;
  margin: 0;
  color: #333;
} 
</style>
  
