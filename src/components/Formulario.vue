<template>
    <div class="container">
        <h2>CONTACT US:</h2>
        <form>
            <div class="row">
                <input type="text" placeholder="Nombre" required>
                <input type="text" placeholder="Apellido" required> 

            </div>
            <div class="row">
                <input type="text" placeholder="Telefono" required>
                <input type="email" placeholder="Email" required>
            </div>
            <textarea name="" id="" cols="30" rows="10" placeholder="Mas info"></textarea>
            <div>
                <button type="submit">Enviar</button>
            </div>
        </form>
    </div>
</template>

<script>
export default {
    name: 'Formulario'
}
</script>

<style scoped>
    .container {
        width: 600px;
        margin: 50px auto;
        display: flex;
        flex-direction: column;
        align-items: center;
    }

    form {
        display: flex;
        flex-direction: column;
        align-items: center;
        border: 4px solid skyblue;
        padding: 20px;
    }

    input {
        width: 240px;
        height: 40px;
        padding-left: 20px;
        margin-bottom: 20px;
    }

    textarea {
        padding: 20px;
        width: 100%;
        margin-bottom: 20px;
    }

    h2 {
        margin-bottom: 40px;
        color: blue;
        font-size: 30px;
    }

    .row {
        width: 500px;
        display: flex;
        justify-content: space-between;
    }

    button {
        width: 150px;
        height: 40px;
    }

    button:hover {
        color: white;
        background: blue;
        transition: 1s;
    }



</style>