<template>
    <a target="_blank" href="https://open.spotify.com/intl-pt/track/2fTTmjyF7pfarDBAbsJkvb?si=5c1a59720aed4e4d">

        <div class="componente">
            <h1>
                "E a Lua ilumina o caminho de casa"
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
const nomeMusica = ref("04AM")
</script>