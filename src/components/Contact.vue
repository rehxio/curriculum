<template>
    <div class="html-contact">
        <div class="contact-title">Contacto</div>
        <div class="Contact">
            <div class="phone">
                <a href="tel:+34686187933">
                    <font-awesome-icon icon="phone" />
                </a>
            </div>
            <div class="mail">
                <a href="mailto:fabianrguezrguez@gmail.com">
                    <font-awesome-icon icon="envelope" />
                </a>
            </div>
            <div class="linkedin">
                <a href="https://www.linkedin.com/in/rehxio">
                    <font-awesome-icon :icon="['fab', 'linkedin']" />
                </a>
            </div>
            <div class="github">
                <a href="https://github.com/rehxio">
                    <font-awesome-icon :icon="['fab', 'github']" />
                </a>
            </div>
        </div>
    </div>
</template>

<style lang="postcss" scoped>
.html-contact {
    font-size: 1.3rem;
}

.contact-title {
    margin-bottom: 25px;
}

.Contact {
    display: grid;
    grid-template-areas: "phone mail linkedin github";
    justify-content: center;

    & .phone,
    .mail,
    .linkedin,
    .github {
        justify-content: space-around;
        font-size: 2rem;
    }
}

a {
    text-decoration: none;
    color: rgb(50, 75, 93);
    background-color: none;
}
</style>
     
        
