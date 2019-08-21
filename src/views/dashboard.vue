<template>
  <h1>TEST</h1>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component({
  components: {}
})
export default class Dashboard extends Vue {
  constructor() {
    super();
  }

  beforeCreate() {
    console.log("before create");
  }

  mounted() {
    console.log("mounted event");
  }
}
</script>