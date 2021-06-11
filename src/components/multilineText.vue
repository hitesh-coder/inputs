<template>
  <div class="mb-5">
    <div class="multilineText d-flex">
      <div class="d-flex flex-column">
        <div class="h3">&lt;Input multilineText /&gt;</div>
        <label for="multilineText1" class="mb-0">
          label
        </label>
        <textarea placeholder="placeholder" id="multilineText1" class="p-2 rounded"></textarea>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    components: {},
  name: "multilineText",
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
}

.flex-column{
  margin-right: 2rem;
}
</style>
