<template>
  <div id="projects" class="row">
    <h2 class="display-4">Products...</h2>
    <div v-for="product in Products" :key="product">
      <div
        class="
          col
          d-flex
          flex-wrap
          justify-content-center
          p-4
          gap-4
        "
      >
        <div class="card rounded-4 text-dark" style="width: 17rem">
          <img
            :src="product.image"
            style="height: 15em"
            class="card-img-top"
            :alt="product.title"
          />
          <div class="card-body">
            <h5 class="card-title p-1">{{ product.title }}</h5>
            <p class="card-text">
              {{ product.desc }}
            </p>
            <div class="d-flex justify-content-center">
                
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  computed: {
    Projects() {
      return this.$store.state.projects;
    },
  },
};
</script>

<style>
#projects {
  padding-top: 10vh;
  min-height: 100vh;
  padding-bottom: 10vh;
}
img{
  object-fit: cover;
}
</style>