<template>
  <div class="about">
    <h1>This is an about page</h1>
     <test-component></test-component>
  </div>
</template>
<script>
// @ is an alias to /src
import TestComponent from "@/components/TestComponent";

export default {
  name: "home",
  components: {
    TestComponent
  }
};
</script>
