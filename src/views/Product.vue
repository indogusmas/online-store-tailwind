<template>
  <section class="text-gray-700 body-font">
    <div  class="container px-5 py-24 mx-auto">
      <div class="flex flex-wrap -m-4">
        <div class="lg:w-1/6 md:w-1/2 p-4 w-full" v-for="product in products" :key="product.id" @click="goToDetail()">
          <a class="block relative h-48 rounded overflow-hidden">
            <img
              alt="ecommerce"
              class="object-fill object-center w-full h-full block"
              src="../assets/product/dress-1.jpg"
            />
          </a>
          <div class="mt-4">
            <h3 class="text-gray-500 text-xs tracking-widest title-font mb-1">
              CATEGORY
            </h3>
            <h2 class="text-gray-900 title-font text-lg font-medium">
              The Catalyzer
            </h2>
            <p class="mt-1">$16.00</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Product",
  data() {
    return {
      products: [
        { id: "1" },
        { id: "2" },
        { id: "3" },
        { id: "4" },
        { id: "5" },
        { id: "6" },
        { id: "7" },
        { id: "8" },
        { id: "9" },
        { id: "10" },
      ],
    };
  },
  methods:{
    goToDetail(){
      this.$router.push({name:"Product-Detail"})
    }
  }
};
</script>
