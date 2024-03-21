<script>
    export default{}
</script>

<template>
<footer>
    <div class="container bottom-menu">
            
        <ul>
            <li><h5>Boolando S.R.L</h5></li>
            <li>
                <nav>
                    <ul class="horizontal-nav">
                        <li> Informazioni legali </li>
                        <li> Informativa sulla privacy </li>
                        <li> Diritto di recesso </li>
                    </ul>
                </nav>
            </li>
         </ul>

         <ul> 
            <li> Trovaci anche su </li>
            <li>
                <nav>
                    <ul class="horizontal-nav">
                        <li><i class="fa-brands fa-twitter"></i></li>
                        <li><i class="fa-brands fa-facebook"></i></li>
                        <li><i class="fa-brands fa-instagram"></i></li>
                        <li><i class="fa-brands fa-pinterest"></i></li>
                        <li><i class="fa-brands fa-youtube"></i></li>
                    </ul>
                </nav>
            </li>
         </ul>

    </div>
</footer>
</template>

<style lang="scss" scoped>

footer{
    display: flex;
    background-color: black;
    color: white;
}

ul {
    list-style: none;
}

li {
    font-size: smaller;
    margin-left: 0px;
    margin-right: 5px;
}

.bottom-menu{
    height: 70px;
    display: flex;
    width: 70%;
    justify-content: space-between;
}

.horizontal-nav{
    display: flex;
    flex-direction: row;
}

</style>