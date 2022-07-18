<template>
  <HeaderSection/>
  <SliderSection/>
  <ImageSection skill="section"/>
  <ImageTextSection skill="section" color="gray"/>
  <CardSection />
  <BannerSection />
  <TextSection />
  <FooterSection />

</template>
<script>
  import HeaderSection from "./components/HeaderSection.vue";
  import SliderSection from "./components/SliderSection.vue";
  import ImageSection from "./components/ImageSection.vue";
  import ImageTextSection from "./components/ImageTextSection.vue";
  import CardSection from "./components/CardSection.vue";
  import BannerSection from "./components/BannerSection.vue";
  import TextSection from "./components/TextSection.vue";
  import FooterSection from "./components/FooterSection.vue";

  export default{
    name:'app',
    components:{
      HeaderSection,
      SliderSection,
      ImageSection,
      ImageTextSection,
      CardSection,
      BannerSection,
      TextSection,
      FooterSection,
    }
  }
</script>
<style>
@import "./App.css";
</style>