<template>
    <a target="_blank" href="https://open.spotify.com/intl-pt/track/4ssHL7bSnOAE7HjiuLx6Co?si=c9667059d5814f7c">

        <div class="componente">
            <h1>
                "Então me diz aê, tu vai matar ou morrer?"
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
const nomeMusica = ref("Crack com Mucilon")
</script>