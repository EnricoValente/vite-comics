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
        .product {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            align-items: center;
            padding: 10px -20px;
            
            
            

            div {
                width: calc(100% / 6);
                
                padding: 10px 10px;
                img {
                    width: 100%;
                    object-fit: cover;
                }

            }

            h6 {
                color: lightgray;
                font-size: 12px;
            }
        }
</style>