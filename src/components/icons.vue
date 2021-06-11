<template>
  <div class="mb-5">
    <div class="icon d-flex">
      <div class="d-flex flex-column-reverse">
        <div class="input-group">
          <label class="input-group-text" id="basic-addon1" for="icon1"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              height="24px"
              viewBox="0 0 24 24"
              width="24px"
              fill="#000000"
            >
              <path d="M0 0h24v24H0V0z" fill="none" />
              <path
                d="M6.54 5c.06.89.21 1.76.45 2.59l-1.2 1.2c-.41-1.2-.67-2.47-.76-3.79h1.51m9.86 12.02c.85.24 1.72.39 2.6.45v1.49c-1.32-.09-2.59-.35-3.8-.75l1.2-1.19M7.5 3H4c-.55 0-1 .45-1 1 0 9.39 7.61 17 17 17 .55 0 1-.45 1-1v-3.49c0-.55-.45-1-1-1-1.24 0-2.45-.2-3.57-.57-.1-.04-.21-.05-.31-.05-.26 0-.51.1-.71.29l-2.2 2.2c-2.83-1.45-5.15-3.76-6.59-6.59l2.2-2.2c.28-.28.36-.67.25-1.02C8.7 6.45 8.5 5.25 8.5 4c0-.55-.45-1-1-1z"
              /></svg
          ></label>
          <input
            type="text"
            placeholder="placeholder"
            id="icon1"
            class="p-2 rounded"
          />
        </div>
        <label for="icon1" class="mb-0"> label </label>
        <div class="h3">&lt;Input startIcon /&gt;</div>
      </div>
      <div class="d-flex flex-column-reverse">
        <div class="input-group">
          <input
            type="text"
            placeholder="placeholder"
            id="icon2"
            class="p-2 rounded"
          />
          <label class="input-group-text" id="basic-addon1" for="icon2"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              height="24px"
              viewBox="0 0 24 24"
              width="24px"
              fill="#000000"
            >
              <path d="M0 0h24v24H0V0z" fill="none" />
              <path
                d="M18 8h-1V6c0-2.76-2.24-5-5-5S7 3.24 7 6v2H6c-1.1 0-2 .9-2 2v10c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V10c0-1.1-.9-2-2-2zM9 6c0-1.66 1.34-3 3-3s3 1.34 3 3v2H9V6zm9 14H6V10h12v10zm-6-3c1.1 0 2-.9 2-2s-.9-2-2-2-2 .9-2 2 .9 2 2 2z"
              /></svg
          ></label>
        </div>
        <label for="icon2" class="mb-0 focus"> label </label>
        <div class="h3">&lt;Input endIcon /&gt;</div>
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

#icon1 {
  outline: none;
}

.flex-column-reverse {
  margin-right: 2rem;
}
</style>
