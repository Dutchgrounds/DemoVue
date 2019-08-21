<template>
  <div id="app">
    <application-menu></application-menu>
    <div id="contentWrapper">
      <router-view></router-view>
      <!-- <snackbar></snackbar>
      <exception-dialog></exception-dialog>-->
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import ApplicationMenu from "@/components/general/the-application-menu.vue";

@Component({
  components: {
    ApplicationMenu
  }
})
export default class App extends Vue {
  constructor() {
    super();
  }
}
</script>
