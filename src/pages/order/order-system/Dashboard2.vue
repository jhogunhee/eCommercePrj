<template>
  <div>
    <h1>1111sadsdasda</h1>
  </div>
</template>

<!--<template>-->
<!--  <div class="product-list">-->
<!--    &lt;!&ndash; Vuestic Grid Layout &ndash;&gt;-->
<!--    <va-grid :columns="4" gap="20px">-->
<!--      &lt;!&ndash; Loop through products and display each card &ndash;&gt;-->
<!--      <div v-for="(product, index) in products" :key="index" class="product-card">-->
<!--        &lt;!&ndash; Product Card Component &ndash;&gt;-->
<!--        <va-card class="product-card-container">-->
<!--          &lt;!&ndash; Product Image &ndash;&gt;-->
<!--          <img :src="product.image" alt="product image" class="product-image"/>-->

<!--          &lt;!&ndash; Product Title &ndash;&gt;-->
<!--          <div class="product-title">{{ product.title }}</div>-->

<!--          &lt;!&ndash; Product Description &ndash;&gt;-->
<!--          <div class="product-description">{{ product.description }}</div>-->

<!--          &lt;!&ndash; Product Price &ndash;&gt;-->
<!--          <div class="product-price">${{ product.price }}</div>-->

<!--          &lt;!&ndash; Button for action (e.g., Add to Cart) &ndash;&gt;-->
<!--          <va-button class="add-to-cart-btn" @click="addToCart(product)">Add to Cart</va-button>-->
<!--        </va-card>-->
<!--      </div>-->
<!--    </va-grid>-->
<!--  </div>-->
<!--</template>-->

<!--<script>-->
<!--export default {-->
<!--  data() {-->
<!--    return {-->
<!--      // Array of products-->
<!--      products: [-->
<!--        {-->
<!--          image: 'https://via.placeholder.com/300',-->
<!--          title: 'Product 1',-->
<!--          description: 'Description for product 1.',-->
<!--          price: 29.99,-->
<!--        },-->
<!--        {-->
<!--          image: 'https://via.placeholder.com/300',-->
<!--          title: 'Product 2',-->
<!--          description: 'Description for product 2.',-->
<!--          price: 49.99,-->
<!--        },-->
<!--        {-->
<!--          image: 'https://via.placeholder.com/300',-->
<!--          title: 'Product 3',-->
<!--          description: 'Description for product 3.',-->
<!--          price: 19.99,-->
<!--        },-->
<!--        {-->
<!--          image: 'https://via.placeholder.com/300',-->
<!--          title: 'Product 4',-->
<!--          description: 'Description for product 4.',-->
<!--          price: 39.99,-->
<!--        }-->
<!--      ]-->
<!--    }-->
<!--  },-->
<!--  methods: {-->
<!--    addToCart(product) {-->
<!--      console.log(`Added ${product.title} to the cart`);-->
<!--    }-->
<!--  }-->
<!--}-->
<!--</script>-->

<!--<style scoped>-->
<!--.product-list {-->
<!--  padding: 20px;-->
<!--}-->

<!--.product-card-container {-->
<!--  width: 100%;-->
<!--  display: flex;-->
<!--  flex-direction: column;-->
<!--  align-items: center;-->
<!--}-->

<!--.product-image {-->
<!--  width: 100%;-->
<!--  height: auto;-->
<!--  border-radius: 10px;-->
<!--}-->

<!--.product-title {-->
<!--  font-size: 1.2rem;-->
<!--  font-weight: bold;-->
<!--  margin-top: 10px;-->
<!--}-->

<!--.product-description {-->
<!--  font-size: 1rem;-->
<!--  color: #555;-->
<!--  margin: 10px 0;-->
<!--}-->

<!--.product-price {-->
<!--  font-size: 1.1rem;-->
<!--  color: #333;-->
<!--  margin: 10px 0;-->
<!--}-->

<!--.add-to-cart-btn {-->
<!--  background-color: #007bff;-->
<!--  color: white;-->
<!--  margin-top: 10px;-->
<!--}-->
<!--</style>-->
