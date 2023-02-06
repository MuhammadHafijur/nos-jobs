<template>
    <div>
        <h1>Job Details Page</h1>
        <p>The jobs id is {{ id }}</p>
    </div>
</template>
<script>
export default {
    data() {
        return {
            id: this.$route.params.id
        }
    }
}
</script>
<style>
    
</style>