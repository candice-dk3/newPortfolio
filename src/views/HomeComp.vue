<template>
    <section id="home">
        <div class="container">
            <div class="text-container">
                <h1>Hi, I am Candice Keet.</h1>
                <h4>aspiring front-end developer</h4>
                <a href="">download resume</a>
            </div>
            <div class="image-container"></div>
        </div>
    </section>
</template>
<script>
export default {
    name: 'HomeComp'
}
</script>
<style scoped>
    .container{
        background-color: #B692C2;
        height: 695px;
        display: grid;
        grid-template-columns: repeat(2, 1fr);
    }
    h1{
        width: 432px;
        height: 313px;
        color: #fff;
        font-size: 70px;
        font-weight: 500;
        text-align: right;
        margin: 170px 0 -20px 250px;
    }
    h4{
        color: #FFF500;
        font-weight: 500;
        text-transform: uppercase;
        margin-left: 350px;
    }
    a{
        text-decoration: none;
        text-transform: uppercase;
        color: #B692C2;
        background-color: #fff;
        height: 31px;
        width: 180px;
        margin-left: 402px;
    }
</style>