<template>
  <h1>TEST</h1>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";

@Component({
  components: {}
})
export default class LifecycleHooks extends Vue {
  constructor() {
    super();
    //https://alligator.io/vuejs/component-lifecycle/
  }

  beforeCreate() {
    console.log("before create");
  }

  mounted() {
    console.log("mounted event");
  }
}
</script>