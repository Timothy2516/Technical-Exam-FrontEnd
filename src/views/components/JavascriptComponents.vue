<template>
    <section class="section section-components" style="background-color: #d6d7d7;">
        <div class="container">
            <modals></modals>
        </div>
        <div class="container">
            <fourColm></fourColm>
        </div>
        <div class="container">
            <imgGif></imgGif>
        </div>
    </section>
</template>
<script>
import Modals from "./JavascriptComponents/Modals";
import FourColm from "./JavascriptComponents/FourColm";
import ImgGif from "./JavascriptComponents/ImgGif";


export default {
  components: {
    Modals,
    ImgGif,
    FourColm
  }
};
</script>
<style>
</style>
