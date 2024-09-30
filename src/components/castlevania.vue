<template>
    <a target="_blank" href="hhttps://open.spotify.com/intl-pt/track/3Kh5a6vXMiJtC35jMEfmyy?si=12918d6665ac4a8a">

        <div class="componente">
            <h1>
                "Ela quer tudo que tá na vitrine, mas ela não <br> quer usar Zara"
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
const nomeMusica = ref("Castlevania")
</script>