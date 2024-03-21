<script>
    export default{}
</script>

<template>
<header>
    <div class="container top-menu">
            
            <nav>
                <button type="button"> Uomo </button>
                <button type="button"> Donna </button>
                <button type="button"> Bambini </button>
            </nav>

            <div class="logo">
                <img src="./assets/img/boolean-logo.png">
            </div>

            <nav>
                <ul>
                    <li><i class="fa-regular fa-user"></i></li>
                    <li><i class="fa-regular fa-heart"></i></li>
                    <li><i class="fa-solid fa-bag-shopping"></i></li>
                </ul>
            </nav>

    </div>
</header>
</template>

<style lang="scss" scoped>

header{
    display: flex;
    background-color: #ff6902;
    color: white;
}

.top-menu{
    height: 50px;
    width: 70%;
    display: flex;
    justify-content: space-between;
    color: white;

    button{
    color: white;
    }

    ul{
    list-style: none;
        li{
        display: inline-block;
        }
    }

}
</style>