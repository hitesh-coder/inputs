<template>
  <div id="inputs" class="p-5">
    <div class="h2">Inputs</div>
    <normal />
    <error />
    <disabled />
    <intersting />
    <icons />
    <values />
    <sizes />
    <fullwidth />
    <multiline-text />

    <footer>
      Created by <a href="https://github.com/hitesh-coder">HITESH</a> -
      devChallenges.io
    </footer>

    <link
      href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600&family=Noto+Sans+JP:wght@400;500&family=Poppins:wght@500&family=Ubuntu+Mono&display=swap"
      rel="stylesheet"
    />
  </div>
</template>

<script>
import Disabled from "./components/disabled.vue";
import Error from "./components/error.vue";
import Fullwidth from "./components/fullwidth.vue";
import Icons from "./components/icons.vue";
import Intersting from "./components/intersting.vue";
import MultilineText from "./components/multilineText.vue";
import normal from "./components/normal.vue";
import Sizes from "./components/sizes.vue";
import Values from "./components/values.vue";

export default {
  name: "App",
  components: {
    normal,
    Error,
    Disabled,
    Intersting,
    Icons,
    Values,
    Sizes,
    Fullwidth,
    MultilineText,
  },
};
</script>

<style lang="scss">
@import "./assets/scss/bootstrap.scss";

.h3 {
  font-family: Ubuntu Mono !important;
  font-size: 1rem !important;
  line-height: 1rem !important;
  /* identical to box height */

  /* Gray 1 */

  color: #333333 !important;
}

.h2 {
  font-family: Poppins !important;
  font-size: 1.5rem !important;
  line-height: 36px !important;
  /* identical to box height */

  /* Gray 2 */

  color: #4f4f4f;
}

label {
  font-family: Noto Sans JP !important;
  font-size: 12px !important;
  line-height: 17px !important;

  /* Gray 1 */

  color: #333333 !important;
}

footer {
  height: 5vh;
  font-family: Montserrat;
  font-style: normal;
  font-weight: 500;
  font-size: 14px;
  line-height: 17px;
  margin-top: 100px;
  text-align: center;
  color: #bdbdbd;
  a {
    font-weight: 700;
    color: #a1a1a1;
  }
}
</style>
