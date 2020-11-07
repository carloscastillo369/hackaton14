<template>
    <div class="container">
        <div class="item">
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eligendi velit cum nam repudiandae minus facilis impedit vero aspernatur iste quis, molestias obcaecati vitae neque, error amet eius asperiores voluptates est tenetur ipsa fugit. Aspernatur laborum corrupti repudiandae nesciunt illum vero ipsum. Ea beatae ex corrupti perspiciatis maiores. Atque, non! Pariatur!.</p>
            <img src="@/assets/area.jpg" alt="">
        </div>

        <div class="item">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam molestiae odio consectetur sint eius at similique dolorum tempora sunt facilis, dolores molestias neque blanditiis libero saepe voluptate culpa beatae officiis laudantium soluta. Repudiandae dolore, accusantium optio impedit mollitia repellat expedita assumenda facere nam provident exercitationem quod hic corrupti voluptatem quidem non. Totam tempore iusto cum ipsam soluta possimus delectus eius cupiditate nulla dicta. Doloribus vel voluptas quaerat maiores dolorum iste.</p>
            <img src="@/assets/nuestro-personal.jpg" alt="">
        </div>

        <div class="item">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus saepe, quas nobis accusantium ducimus voluptates, aliquam ipsa hic, non iure dolore? Facere vitae cumque magnam ducimus quam accusantium saepe voluptate ex perspiciatis repellat rem eveniet dolore praesentium consequatur eos quidem aut quos debitis quo reiciendis, eum laboriosam deserunt? Voluptates commodi adipisci ipsa ratione minus tempora quod sit cum id ut cupiditate provident iste non impedit unde, quibusdam ipsam placeat repellat incidunt pariatur laborum nobis fugit. Ex praesentium, quam quis, suscipit blanditiis aliquam fuga error vitae quibusdam aperiam illo reiciendis earum placeat recusandae. Iusto sequi facilis aliquid quae, ipsum odit quaerat.</p>
            <img src="@/assets/instalaciones.jpg" alt="">
        </div>

    </div>
</template>

<script>
export default {
    name:'Products'

}
</script>

<style scoped>

    .container {
        width: 700px;
        margin: 30px auto;
        display: flex;
        flex-wrap: wrap;
    }

    .item {
        display: flex;
        margin-bottom: 30px;
        align-items: center;
    }

    img {
        width: 200px;
        display: block;
        margin-left: 20px;
    }

    p {
        color: rgb(59, 147, 182);
    }

</style>