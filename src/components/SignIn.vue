<template>
    <div id="contenido">
        <img src="imagenes/LogoMakr-8eG4zk.png" alt="" />

        <section id="formulario">
            <h1>Sign In</h1>
            <input class="control" type="text" placeholder="Email or phone number" />
            <input class="control" type="password" placeholder="Password" />

            <button class="control boton" @click="signIn">Sign in</button>
            <label><input type="checkbox" />Remember me</label>
            <a href="#" id="help-link">Need help</a>
            <div id="texto-prueba">Texto visible solo en pantallas grandes</div>
        </section>
    </div>
</template>

<script setup>
import { ref } from 'vue'

const signIn = () => {
    // Add your sign in logic here
}
</script>

<style scoped>
#contenido {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 50px;
}

#formulario {
    width: 300px;
    padding: 20px;
    border: 1px solid #ccc;
    border-radius: 8px;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
}

@media (max-width: 768px) {
    #formulario {
        width: 90%;
        /* Adjust width for smaller screens */
    }
}
</style>
