<template>
    <div>
        <h1>My firts components!</h1>
        <span>{{ color }}</span>
    </div>
</template>



<script>

export default {
    data() {
        return {
            color:'red'
        }
    }
}

</script>

<style>
h1 {
    font-family: 'Avenir', Arial, Helvetica, sans-serif;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>