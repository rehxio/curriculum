<template>
    <div class="html-menu">
        <div class="OptionsCV">
            <div class="datos htmlButton">Datos Personales</div>
            <div class="estudios htmlButton">Estudios</div>
            <div class="explaboral htmlButton">Experiencia Laboral</div>
            <div class="conocimientos htmlButton">Conocimientos</div>
        </div>
    </div>
</template>

<style lang="postcss" scoped>
.html-menu {
    margin-top: 3rem;
    justify-content: center;
    display: grid;
    grid-template-areas:
        "datos"
        "estudios"
        "explaboral"
        "conocimientos";
}

.htmlButton {
    width: 13rem;
    background-image: linear-gradient(to top right, rgb(0, 183, 134), rgb(64, 112, 146));
    border-radius: 5px;
    padding: 15px;
    margin: 15px 0;
    color: whitesmoke;
    font-size: 1.2rem;
    font-weight: 700;
    text-align: center;
}
</style>


