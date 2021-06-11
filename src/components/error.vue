<template>
  <div class="mb-5">
    <div class="error d-flex">
      <div class="d-flex flex-column-reverse">
        <input
          type="text"
          placeholder="placeholder"
          id="error1"
          class="p-2 rounded"
        />
        <label for="error1" class="mb-0"> label </label>
        <div class="h3">&lt;Input error /&gt;</div>
      </div>
      <div class="d-flex flex-column-reverse">
        <input
          type="text"
          placeholder="placeholder"
          id="error2"
          class="p-2 rounded"
        />
        <label for="error2" class="mb-0"> label </label>
        <div class="h3">&amp;hover</div>
      </div>
      <div class="d-flex flex-column-reverse">
        <input
          type="text"
          placeholder="placeholder"
          id="error3"
          class="p-2 rounded"
        />
        <label for="error3" class="mb-0 focus"> label </label>
        <div class="h3">&amp;focus</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "error",
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

input:focus,
#error3,
.focus {
  border-color: $danger !important;
  color: $danger;
}

input:focus + label {
  color: $danger !important;
}

.flex-column-reverse {
  margin-right: 2rem;
}
</style>
