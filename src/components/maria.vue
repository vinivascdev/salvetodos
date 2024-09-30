<template>
    <a target="_blank" href="https://open.spotify.com/intl-pt/track/2ux3Sb90r5aA74nLMls1u0?si=f9796fc8f0a64277">

        <div class="componente">
            <h1>
                "Vem clarear a minha noite, me mostrar o <br>caminho que antes eu não via"
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
const nomeMusica = ref("Maria")
</script>