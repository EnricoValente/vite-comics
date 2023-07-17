<script>
    export default {
    data() {
      return {
        
      }
    },
    props: {
        productImage:String,
        productTitle:String
    }
  }
</script>

<template>
    <div class="product">
        <div v-for="(product, productIndex) in products" :key="productIndex">
            <img :src="productImage" alt="">

            
        </div>
        
        <h6>
            {{ productTitle }}
        </h6>
    </div>
</template>


<style scoped lang="scss">
       
</style>