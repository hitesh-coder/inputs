<template>
  <div class="mb-5">
    <div class="fullwidth d-flex">
      <div class="d-flex flex-column">
        <div class="h3">&lt;Input fullwidth /&gt;</div>
        <label for="fullwidth1" class="mb-0">
          label
        </label>
        <input type="text" placeholder="placeholder" id="fullwidth1" class="p-2 rounded">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "fullwidth",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/scss/bootstrap.scss";

input{
  border-color: $gray-400;
  border-width: 1px !important;
  border-style: solid;
  outline: none;
  width: 90vw;
}

.flex-column{
  margin-right: 2rem;
}
</style>
