<template>
    <header>
        <Logo/>
    </header>
    <div>
        {{ color }}
    </div>
</template>

<script setup>
import Logo from '../components/Logo.vue'
const color = 'red'

</script>