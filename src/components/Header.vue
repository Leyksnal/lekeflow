<template>
    <div class="hero">
        <div class="navbar">
        <!-- <img src="./img/favicon0.png" alt="" class="logo"> -->
        <button type="button">Chat me</button>
        </div>
    </div>
</template>



<script>
export default {
    name: 'Header'
}
</script>


<style scoped>

.hero{
    width: 100%;
    height: 100vh;
    background-position: center;
    position: relative;
    overflow: hidden;
}

.logo{
    width: 100px;
    cursor: pointer;
}

.navbar{
    width: 90%;
    height: 15%;
    margin: auto;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

button{
    color: #fbfcfd;
    padding: 10px 20px;
    background: transparent;
    border-radius: 25px;
    border: 1px solid #fff;
    outline: none;
    cursor: pointer;
}


</style>