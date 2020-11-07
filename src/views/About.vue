<template>
    <div>
        <Saludo/>
        <Products/>
    </div>
  
</template>

<script>
import Saludo from "@/components/Saludo.vue";
import Products from "@/components/Products.vue";

export default {
    name: 'About',
    components: {
        Saludo,
        Products
  }
}
</script>

<style>

</style>