<template>
    <div class='container'>
        <div class='header'>
            <h1>Fabián Rodríguez Rodríguez</h1>
        </div>
        <div class='menu'>
            <html-menu></html-menu>
        </div>
        <div class="contact">
            <html-contact></html-contact>
        </div>
        <div class='content'>
            <img src="./assets/logo.png" alt="Foto de Fabián">
        </div>
    </div>
</template>

<style lang="postcss" scoped>
.header {
    grid-area: header;
    text-align: center;

    & h1 {
        font-family: Montserrat, Impact, sans-serif;
        font-size: 48px;
    }
}

.menu {
    grid-area: menu;
}

.content {
    grid-area: content;
}

.footer {
    grid-area: footer;
}

.contact {
    grid-area: contact;
    justify-content: center;
    text-align: center;
}

.container {
    display: grid;
    grid-template-areas:
        "header header header header header header header"
        "menu content content content content content content"
        "menu content content content content content content"
        "contact content content content content content content";
}
</style>

<script>
import Menu from "./components/Menu";
import Contact from "./components/Contact";
export default {
    components: {
    'html-menu': Menu,
    'html-contact': Contact
  }
};
</script>
