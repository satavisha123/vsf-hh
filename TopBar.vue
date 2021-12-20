<template>
  <div class="for-topbar">
    <div>
      <ul class="list">
        <li class="item"><a>Home Furniture</a></li>
        <li class="item"><a> Homes & Cottages</a></li>
        <li class="item"><a>BeautiTone</a></li>
      </ul>
    </div>
    <div>
      <div class="middle"><b>FREE SHIPPING</b><a> a store eligible order</a></div>
    </div>
    <div class="language">
      <a
        href=" https://www.homehardware.ca/fr/"
        data-mz-lang="languageChangeLink"
        title="Français"
        class="mz-utilitynav-link"
        data-gtm-vis-recent-on-screen-8904058_1287="8072"
        data-gtm-vis-first-on-screen-8904058_1287="8072"
        data-gtm-vis-total-visible-time-8904058_1287="100"
        data-gtm-vis-has-fired-8904058_1287="1"
        >Français</a
      >
    </div>
  </div>
</template>

<script>
import { SfButton, SfTopBar } from "@storefront-ui/vue";
import LocaleSelector from "./LocaleSelector";

export default {
  components: {
    SfTopBar,
    SfButton,
    LocaleSelector,
  },
};
</script>
<style lang="scss" scoped>
.topbar {
  position: relative;
  z-index: 2;
  &__button {
    margin: 0 0 0 var(--spacer-xs);
  }
}
.for-topbar {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
}

.list {
  list-style: none;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  font-family: Agenda, sans-serif;
}
.middle{
  padding: 15px;
  font-family: Agenda, sans-serif;
}
.middle:hover{
   text-decoration: underline;
}
.item {
  color: black;
  font-size: 14px;
  line-height: 14px;
  border-left: 1px solid #000;
  /* padding-right: 14px; */
  padding-left: 14px;
  float: left;
  line-height: 20px;
  text-decoration: underline;
}

.language{
  padding-left: 300px;
    padding-top: 15px;
}
.language:hover{
   text-decoration: underline;
}
</style>
