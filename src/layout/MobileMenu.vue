<template>
<!--  ><md-list-item-->
<!--    href="https://www.instagram.com/CreativeTimOfficial"-->
<!--    target="_blank"-->
<!--  >-->
<!--    <i class="fab fa-instagram"></i>-->
<!--    <p class="hidden-lg">Instagram</p>-->
<!--    <md-tooltip md-direction="bottom">Follow us on Instagram</md-tooltip>-->
<!--  </md-list-item>-->
  <md-list
    class="nav-mobile-menu nav-mobile-section-start"
    v-if="navMobileSectionStart === 'true'"
  >
  </md-list>
</template>

<script>
export default {
  name: "mobile-menu",
  props: {
    navMobileSectionStart: {
      type: String,
      default: "false"
    }
  }
};
</script>
