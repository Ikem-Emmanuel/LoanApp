<template>
  <div id="dashboard" class="h-screen flex flex-col justify-items-center">
    <Header />
    <Form />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import Header from "@/components/Header.vue";
import Form from "@/components/Forms.vue";
import Footer from "@/components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Form,
    Footer
  }
};
</script>

<style></style>
