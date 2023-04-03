<template>
    <div id="main-banner">
        <h1>Make Your Burguer</h1>
    </div>
</template>

<script>
export default {
    name: "Banner"
}
</script>

<style scoped>
    #main-banner {
        
        background: url('https://i.pinimg.com/originals/d8/8a/ca/d88acacdd20c6e4af73520058cb85aca.jpg');
        background-position: 0;
        background-size: cover;
        height: 500px;
        display:flex;
        align-items: center;
        justify-content: flex-start;
    }

    h1{
        color: #fff;
        text-align: center;
        font-size: 60px;
        background-color: #222;
        padding: 20px 40px;
    }
</style>