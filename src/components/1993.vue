<template>
    <a target="_blank" href="https://open.spotify.com/intl-pt/track/6QsHhB0W9GtLF3cI7mUVkQ?si=65c806a039224359">

        <div class="componente">
            <h1>
                "Nada disso passava de um sonho distante"
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
const nomeMusica = ref("1993")
</script>