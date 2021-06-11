<template>
    <div class="mb-5">
        <div class="intersting d-flex">
            <div class="d-flex flex-column-reverse">
                <div>
                    <input
                        type="text"
                        placeholder="placeholder"
                        id="intersting1"
                        class="p-2 rounded"
                    />
                    <br>
                    <label class="h6 m-0">Some interesting text</label>
                </div>
                <label for="intersting1" class="mb-0"> label </label>
                <div class="h3">
                    &lt;Input helperText="Some intersting text" /&gt;
                </div>
            </div>
            <div class="d-flex flex-column-reverse">
                <div>
                    <input
                        type="text"
                        placeholder="placeholder"
                        id="intersting2"
                        class="p-2 rounded"
                    />
                    <br>
                    <label class="h6 m-0 focus">Some interesting text</label>
                </div>
                <label for="intersting2" class="mb-0 focus"> label </label>
                <div class="h3">
                    &lt;Input helperText="Some intersting text" error/&gt;
                </div>
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
#intersting2,
.focus {
    border-color: $danger !important;
    color: $danger;
}

input:focus + .h6 {
    color: $danger !important;
}

.flex-column-reverse {
    margin-right: 2rem;
}
</style>