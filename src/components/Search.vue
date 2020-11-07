<template>
    <div class="container">
        <h2>ID Paciente</h2>
        <input type="text" placeholder="Cod. Identificación">
        <button>Buscar</button>
    </div>
</template>

<script>
export default {
    name: 'Search',
    paciente: ''
}
</script>

<style scoped>
    .container {
        margin: 20px auto;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    h2 {
        font-size: 20px;
        color: darkblue;
    }

    input {
        margin-left: 20px;
        width: 200px;
        height: 35px;
        padding-left: 10px;
    }

    button {
        margin-left: 20px;
        width: 70px;
        height: 35px;
        border: unset;
        border-radius: 4px;
        border: 1px solid black;
    }

    button:hover {
        background: blue;
        color: white;
        transition: 0.5s;
    }
</style>