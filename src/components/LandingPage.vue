<template>
    <header id="home">
        <div class="text">
            <h1>Welcome</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Assumenda, similique?</p>
        </div>
        <div class="gambar">
            <img src="./../assets/contoh produk.png" alt="Produk">
        </div>
        <a href="#about">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="white"
                class="size-6">
                <path stroke-linecap="round" stroke-linejoin="round"
                    d="m4.5 5.25 7.5 7.5 7.5-7.5m-15 6 7.5 7.5 7.5-7.5" />
            </svg>
        </a>
        <span class="neon"></span>
        <span class="left"></span>
        <span class="right"></span>
    </header>
</template>
<script>
export default {

}
</script>
<style scoped>
header {
    display: flex;
    flex-wrap: wrap;
    padding: 100px;
    justify-content: space-evenly;
    align-items: center;
}

.text {
    width: 50%;
}

.text h1 {
    font-size: 100px;
    padding: 5px;
    /* text-align: center; */
    text-shadow: 0 0 100px white;
}

.text p {
    font-size: 20px;
    padding: 5px;
    text-align: justify;
}

.gambar {
    width: 50%;
    text-align: center;
}

.gambar img {
    width: 100%;
}

a svg {
    position: absolute;
    width: 2%;
    bottom: 1%;
    right: 50%;
}

.neon {
    /* background-color: white; */
    position: absolute;
    width: 25%;
    height: 50%;
    right: 16.5%;
    top: 27%;
    border-radius: 50%;
    border: white solid 5px;
    box-shadow: 0 0 20px white;
}

.left {
    background-color: white;
    position: absolute;
    width: 200px;
    height: 200px;
    left: 50%;
    top: 100px;
    border-radius: 50%;
    box-shadow: 0 0 20px gray;
}

.right {
    background-color: white;
    position: absolute;
    width: 150px;
    height: 150px;
    right: 10%;
    bottom: 100px;
    border-radius: 50%;
    box-shadow: 0 0 20px white;
}

@media screen and (max-width:780px) {
    header{
        padding: 10px;
        flex-direction: column-reverse;
    }
    .text h1{
        font-size: 20px;
    }
    .text p{
        font-size: 10px;
    }
    .right , .left , .neon{
        display: none;
    }
    a svg{
        display: none;
    }
}
</style>