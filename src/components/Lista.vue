<template>
    <div class="container">
        <h2>LISTA DE PACIENTES:</h2> 
        <ul class="tabla">
            <li>
                <ul class="fila-main">
                    <li class="col-1">Nº</li>
                    <li class="col-2">Nombre</li>
                    <li class="col-3">Email</li>
                </ul>
            </li>
            <li v-for="usuario in usuarios" :key='usuario.id'> 
                <ul class="fila">
                    <li class="col-1">{{usuario.id}}</li>
                    <li class="col-2">{{usuario.name}}</li>
                    <li class="col-3">{{usuario.email}}</li>
                </ul>
            </li>
        </ul>
    </div>
  
</template>

<script>
export default {
    name:'Lista',
    data(){
        return{
            usuarios: [],
        }
    },

    methods: {
        async getInfoUsers(){
            const info = await fetch('http://jsonplaceholder.typicode.com/users')
            const data = await info.json();
            this.usuarios = data;
        }
    },

    created() {
        this.getInfoUsers();
    }

}
</script>

<style scoped>
    .container {
        display: flex;
        flex-direction: column;
        align-items: center;
        margin: 40px auto;
    }

    h2 {
        font-size: 30px;
        margin-bottom: 50px;
        color: blue;
    }

    ul {
        list-style: none;
    }

    .tabla {
        width: 700px;
        border: 1px solid black;
        color: blue;
    }

    .fila-main {
        display: flex;
        align-items: center;
        border-bottom: 1px solid skyblue;
        height: 30px;
        color: black;
        font-weight: bold;
        background: skyblue;
    }
    
    .fila {
        display: flex;
        align-items: center;
        border-bottom: 1px solid skyblue;
        height: 30px;
    }

    .col-1 {
        width: 100px;
        text-align: center;
    }

    .col-2 {
        width: 300px;
    }

    .col-3 {
        width: 300px;
    }

</style>