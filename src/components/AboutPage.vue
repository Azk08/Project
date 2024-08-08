<template>
    <main class="about">
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

.text {
    width: 50%;
    text-align: justify;
}

.gambar {
    width: 40%;
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