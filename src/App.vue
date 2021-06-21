<template>
  <v-app>
    <HeaderComponent/>
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
import HeaderComponent from './components/header.component'
export default {
  name: "App",
  components: {
    HeaderComponent,
  },
};
</script>
<style>
.v-application--wrap {
  background: radial-gradient(33.06% 65.37% at 100% 100%, rgba(255, 255, 255, 0.2) 0%, rgba(0, 0, 0, 0) 100%), radial-gradient(39.72% 78.55% at 4.79% 7.96%, rgba(255, 255, 255, 0.2) 0%, rgba(7, 33, 66, 0.094) 100%), #072142;
}
</style>
