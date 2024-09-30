<template>
    <a target="_blank" href="https://open.spotify.com/intl-pt/track/3Sa2gVQioE31DcG4nKNDqD?si=fbb07ba194734cb3">

        <div class="componente">
            <h1>
                "Único hash que eu conheço eu fumo"
            </h1>

            <h3>
                - {{ nomeArtista }}, {{ nomeMusica }}.
            </h3>
            
        </div>
    </a>
</template>

<script setup>
import { ref } from "vue"
const nomeArtista = ref("Brandão085")
const nomeMusica = ref("Isso é Sério")
</script>