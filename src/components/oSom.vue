<template>
    <a target="_blank" href="hhttps://open.spotify.com/intl-pt/track/4v0VOuuaZSQHjnjzkC3cnk?si=93c96a20e81147e6">

        <div class="componente">
            <h1>
                "Além daqui, dessa visão, pude sentir <br>meu coração"
            </h1>

            <h3>
                - {{ nomeArtista }}, {{ nomeMusica }}.
            </h3>

        </div>
    </a>
</template>

<script setup>
import { ref } from "vue"
const nomeArtista = ref("Matuê")
const nomeMusica = ref("O Som")
</script>