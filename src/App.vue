<template>
  <div class='container'>
    <div class='header'>
      <h1>Fabián Rodríguez Rodríguez</h1>
    </div>
    <div class='contact'>
      <html-contact></html-contact>
    </div>
    <div class='content'>
      <img src="./assets/logo.png" alt="Foto de Fabián">
    </div>
  </div>
</template>

<style>
.header {
  grid-area: header;
}

.contact {
  grid-area: contact;
}

.content {
  grid-area: content;
}

.footer {
  grid-area: footer;
}

.container {
  display: grid;
  grid-template-areas:
    "header header header header header header"
    "contact content content content content content";

  text-align: center;
}

h1 {
  font-family: Montserrat, Impact, sans-serif;
  font-size: 48px;
}
</style>

<script>
import Contact from "./components/Contact";
export default {
  components: {
    "html-contact": Contact
  }
};
</script>
