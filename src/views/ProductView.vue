<template>
  <div class="container-fluid">
    <div class="row">
        <div class="col">
            <Card/>
        </div>
    </div>
  </div>
</template>

<script>
import Card from '../components/ProductsCard.vue';

export default {
comonents: { Card },
}
</script>

<style scoped>
.container-fluid {
    min-height: 88vh;
}
</style>