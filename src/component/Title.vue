<template>
    <div>
        <h2>{{ title }}</h2>
    </div>
</template>

<script>
export default {
    props:{
        title: String,
    }
}
</script>

<style scoped>
h2{
    color: blueviolet;
}
</style>