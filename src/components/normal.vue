<template>
  <div class="mb-5">
    <div class="normal d-flex">
      <div class="d-flex flex-column">
        <div class="h3">&lt;Input /&gt;</div>
        <label for="normal1" class="mb-0"> label </label>
        <input
          type="text"
          placeholder="placeholder"
          id="normal1"
          class="p-2 rounded"
        />
      </div>
      <div class="d-flex flex-column">
        <div class="h3">&amp;hover</div>
        <label for="normal2" class="mb-0"> label </label>
        <input
          type="text"
          placeholder="placeholder"
          id="normal2"
          class="p-2 rounded"
        />
      </div>
      <div class="d-flex flex-column">
        <div class="h3">&amp;focus</div>
        <label for="normal3" class="mb-0"> label </label>
        <input
          type="text"
          placeholder="placeholder"
          id="normal3"
          class="p-2 rounded"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "normal",
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
#normal3 {
  border-color: $primary !important;
}

.flex-column {
  margin-right: 2rem;
}

.h3 {
  font-family: Ubuntu Mono;
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  line-height: 12px;
  /* identical to box height */

  /* Gray 1 */

  color: #333333;
}
</style>
