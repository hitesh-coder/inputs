<template>
  <div class="mb-5">
    <div class="size d-flex">
      <div class="d-flex flex-column">
        <div class="h3">&lt;Input size="sm" /&gt;</div>
        <label for="size1" class="mb-0"> label </label>
        <input
          type="text"
          placeholder="placeholder"
          id="size1"
          class="p-2 rounded"
        />
      </div>
      <div class="d-flex flex-column">
        <div class="h3">&lt;Input size="md" /&gt;</div>
        <label for="size2" class="mb-0"> label </label>
        <input
          type="text"
          placeholder="placeholder"
          id="size2"
          class="p-3 rounded"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "sizes",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/scss/bootstrap.scss";

input {
  border-color: $gray-400;
  border-width: 1px !important;
  border-style: solid;
  outline: none;
}

.flex-column {
  margin-right: 2rem;
}
</style>
