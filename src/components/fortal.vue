<template>
    <a target="_blank" href="https://open.spotify.com/intl-pt/track/6OcZP4rUfuxms2r8Mwx5BQ?si=534bba13554f4d65">

        <div class="componente">
            <h1>
                "Quem tem cabeça que crie seu gado"
            </h1>

            <h3>
                - {{ nomeArtista }}, {{ nomeMusica }}.
            </h3>
            
        </div>
    </a>
</template>

<script setup>
import { ref } from "vue"
const nomeArtista = ref("Matuê e Teto")
const nomeMusica = ref("4tal")
</script>