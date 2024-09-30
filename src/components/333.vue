<template>
    <a target="_blank" href="https://open.spotify.com/intl-pt/track/4v0VOuuaZSQHjnjzkC3cnk?si=b49995345d34454e">
        <div class="componente">
            <h1>"Além da visão, além da visão, força"</h1>
            <h3>- {{ nomeArtista }}, {{ nomeMusica }}.</h3>
        </div>
    </a>
</template>

<script setup>
import { ref } from "vue"
const nomeArtista = ref("Matuê")
const nomeMusica = ref("333")
</script>