<template>
    <div id="main-banner">
        <h1>Make Your Burger</h1>
    </div>
</template>

<script>
export default {
    name: "Banner"
}
</script>

<style scoped>
    #main-banner{
        background-image: url('/public/img/burger.jpg');
        background-position: 0 -250px;
        background-size: cover;
        height: 500px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }
    #main-banner h1{
        font-size: 60px;
        color: #fff;
        text-align: center;
        background-color: #222;
        padding: 20px 40px;
        border-top-right-radius: 10px;
        border-bottom-right-radius: 10px;
    }
</style>