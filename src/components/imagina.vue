<template>
    <a target="_blank" href="https://open.spotify.com/intl-pt/track/2fjqfFUq64thFsqfKN01kS?si=f654e8173ab94c5f">

        <div class="componente">
            <h1>
                "Que a sede não me faça beber do copo errado"
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
const nomeMusica = ref("Imagina Esse Cenário")
</script>