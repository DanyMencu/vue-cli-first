<template>
    <div class="container">
        <img src="../assets/hero-img.png" alt="">
        <h3>Lorem ipsum dolor sit amet consectetur adipisicing elit. At quos molestias a ea dicta similique maxime asperiores dolorum, distinctio placeat exercitationem alias, ab aspernatur excepturi consequatur nesciunt inventore sed cum.</h3>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    .container {
        height: 45vh;
        width: 100%;
        position: relative;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .container img {
        width: 100%;
        height: 100%;
        object-fit: cover;
    }
    .container h3 {
    width: 50%;
    position: absolute;
    margin: 0;
    padding: 5px;
    font-weight: 600;
    line-height: 20px;
    color: #fff;
    background: rgba(0, 0, 0, 0.7);
    border: 1px solid #000;
    border-radius: 10px;
    }
</style>