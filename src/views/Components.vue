<template>
    <div>
        <carousel></carousel>
        <javascript-components></javascript-components>
    </div>
</template>
<script>
import Carousel from "./components/Carousel";
import JavascriptComponents from "./components/JavascriptComponents";

export default {
  name: "components",
  components: {
    Carousel,
    JavascriptComponents,
  }
};
</script>
