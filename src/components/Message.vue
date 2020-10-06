<template>
    <div class="comment">
        <p>{{comment}}</p>
    </div>
</template>

<script>
export default {
    name: 'Message',
    props: {
        comment: String
    }
}
</script>

<style scoped>
p {
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
</style>