<template>
    <div id="intro">
        <div class="logo"><img src="../assets/gitty_logo.jpg"></div>
        <div class="caption">
            <h1>Gitty The Github helper</h1>
            <p> Get the most out of your discord bot for your open source org</p>
        </div>
        <div class="buttons">
            <a class="btn btn-lg" href="https://bit.ly/37R8d20"><i class="fab fa-discord"></i> Add to Discord</a>
            <a class="btn btn-lg" href="#features">See features</a>
        </div>
    </div>
</template>


<script>
export default {
    
}
</script>


<style scoped>
#intro{
    background-color: #edf057;
}

.logo{
    text-align: center;
}

.caption{
    text-align: center;
}
.caption h1{
    font-weight: bold;
}

.caption p{
    font-size: 2rem;
}

.buttons {
    text-align: center;
    
}

.buttons a:nth-child(1){
    margin: 10px;
    background-color: #32c5f2;
    color: white;
    font-weight: 500;
}

.buttons a:nth-child(1) i{
    margin-right: 15px;
    color: white;
    font-weight: 100;
    font-size: 25px;
}

.buttons a:nth-child(2){
    margin: 10px;
    background-color: #000000;
    color: white;
    font-weight: 500;
}




</style>