<template>
  <div>
    <NavOne />
    <PageHeader title="Infrastructures" image="/assets/images/markets.jpg" />
    <Infrastructure />
   
    <div class="border-bottom"></div>
    <Gallery />
    <CallToActionOne />
    <Footer />
  </div>

</template>
<script>
  import NavOne from "../components/NavOne";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import Infrastructure from "../components/Infrastructure";
   import Gallery from "../components/Gallery";
  
  import CallToActionOne from "../components/CallToActionOne";
  export default {
    components: {
      CallToActionOne,
      Gallery,
      Infrastructure,
      Footer,
      PageHeader,
      NavOne
    },
    head(){
      return {
        title: "ADFG | Infrastructures"
      }
    }
  }
</script>
