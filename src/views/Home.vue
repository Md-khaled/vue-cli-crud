<template>
  <div>
    <ProductList></ProductList>
  </div>
</template>

<script>
// @ is an alias to /src
import ProductList from '@/components/ProductList.vue'

export default {
  name: 'MasterPage',
  components: {
    ProductList,
  },
}
</script>
