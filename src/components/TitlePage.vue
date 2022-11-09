<template>
    <h1>{{ title }}</h1>
</template>
  
<script>
export default {
    name: 'TitlePage',
    data() {
        return {
            title: "La mia prima app con Vite!"
        }
    }
}
</script>

  
<style lang="css" scoped>
h1 {
    text-align: center;
}
</style>