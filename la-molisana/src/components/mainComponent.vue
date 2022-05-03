<template>
  <main>
    <h1>Lista Prodotti</h1>
    <productList/>
    
  </main>
</template>

<script>
import productList from '@/components/productList.vue'
export default {
  name: "mainComponent",
  components: {
      productList
  },
  
};
</script>