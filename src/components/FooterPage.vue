<template>
    <footer>
        <h1>Thank you</h1>
        <p>Create by &copy;AZK08. Assets by &copy;<a href="">HeroIcons</a> and &copy;<a href="">Icons8</a></p>
    </footer>
</template>
<script>
export default {

}
</script>
<style scoped>
footer {
    text-align: center;
    padding: 100px;
}

a {
    text-decoration: none;
    color: white;
}

@media screen and (max-width: 780px) {
    footer{
        padding: 10px;
        margin-top: 100px;
    }
    h1{
        font-size: 15px;
    }
    p{
        font-size: 10px;
    }
}
</style>