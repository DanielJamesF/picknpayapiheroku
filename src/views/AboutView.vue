<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col">
        <h1>ピックアンドペイ</h1>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container-fluid {
  height: 88vh;

  background: linear-gradient(
    90deg,
    rgba(2, 0, 36, 1) 0%,
    rgba(9, 9, 121, 1) 35%,
    rgb(255, 0, 0) 100%
  );
}
.row {
  height: 100%;
  display: flex;
  align-items: center;
}
h1 {
  font-size: 100px;
  color: white;
}
</style>