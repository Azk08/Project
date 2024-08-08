<template>
    <main class="about" id="about">
        <div class="gambar">
            <img src="./../assets/logo.png" alt="">
        </div>
        <div class="text">
            <h1>About</h1>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptas beatae architecto perspiciatis ipsam?
                Rem
                aperiam laborum, illum iste laboriosam error id recusandae est blanditiis, nisi at earum! Aliquid sint
                quos
                ratione! In esse placeat similique neque necessitatibus accusantium corporis excepturi atque cum
                blanditiis
                voluptatum architecto dolores hic, totam quas eveniet?</p>
        </div>
        <!-- <span class="lightbar"></span> -->
        <!-- <p class="mark">&copy;AZK08</p> -->
    </main>
</template>
<script>
export default {

}
</script>
<style scoped>
.about {
    display: flex;
    flex-wrap: wrap;
    /* justify-content: space-around; */
    align-items: center;
    justify-content: space-around;
    padding: 100px;
    /* margin-top: ; */

    
}

@media screen and (max-width:780px) {
    .about{
        padding: 10px;
        /* flex-direction: column; */
        flex-direction: column;
        margin-top: 100px;
    }
    .text h1 {
        font-size: 15px;
        text-align: center;
        text-shadow: 0 0 15px white;
        backdrop-filter: blur(2px);
        border-radius: 50%;
    }
    .text p{
        font-size: 10px;
        backdrop-filter: blur(2px);
        text-shadow: 0 0 15px white;
    }
    .text{
        z-index: 1;
        position: absolute;
    }
    .gambar img{
        z-index: 0;
    }
}


.text {
    width: 50%;
    text-align: justify;
}

.gambar {
    width: 50%;
}


.gambar img{
    width: 100%;
}

/* .lightbar {
    height: 1px;
    width: 100%;
    background-color: white;
    border: 1px solid white;
    box-shadow: 0 0 50px white;
} */

/* .mark p {
    color: gray;
    opacity: 10;
} */ 
</style>