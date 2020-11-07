<template>
    <div class="container">
        <img src="@/assets/jumbo.jpg" alt="">
        <h2>
        Connecting patiens <br> & medical organizations
        </h2>
    </div>
</template>

<script>
export default {
    name: 'Jumbotron'
}
</script>

<style scoped>
    .container {
        display: flex;
        flex-direction: column;
        align-items: center;
        margin: 30px auto;
    }

    h2 {
        text-align: center;
        color: blue;
        font-size: 50px;
    }

    img {
        height: 320px;
    }
</style>