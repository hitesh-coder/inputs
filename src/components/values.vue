<template>
  <div class="mb-5">
    <div class="value d-flex">
      <div class="d-flex flex-column-reverse">
        <input
          type="text"
          placeholder="placeholder"
          id="value1"
          class="p-2 rounded"
          value="text"
        />
        <label for="value1" class="mb-0"> label </label>
        <div class="h3">&lt;Input value="text" /&gt;</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "values",
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

.flex-column-reverse {
  margin-right: 2rem;
}
</style>
