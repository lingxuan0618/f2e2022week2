<template>
  <div class="d-flex flex-column" style="height:100vh;">
    <HeaderNav/>
    <router-view/>
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderNav from '@/components/HeaderNav.vue';

export default {
  components: {
    HeaderNav,
  },
};
</script>
<style lang="scss">
@font-face{
  font-family: custom-pixel;
  src: url(./assets/font/NotoSansTC-Medium.otf);
}
body {
  font-family: custom-pixel;
}
nav {
  padding: 30px;
  a {
    font-weight: bold;
    text-decoration: none;
  }
}
</style>
