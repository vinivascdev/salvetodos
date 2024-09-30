<template>
    <a target="_blank" href="https://open.spotify.com/intl-pt/track/7pMfMzfYSTbNxj5lJEbQIp?si=0b00d44e261e462d">

        <div class="componente">
            <h1>
                "Me veio num sonho e revelou algo que eu <br>não queria enxergar"
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
const nomeMusica = ref("V de Vilão")
</script>