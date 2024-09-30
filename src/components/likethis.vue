<template>
    <a target="_blank" href="https://open.spotify.com/intl-pt/track/49gGZLLm1d7fBFQkTqskXo?si=ee33545ed07f41c7">

        <div class="componente">
            <h1>
                "I was lost, but now I'm found again"
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
const nomeMusica = ref("Like This!")
</script>