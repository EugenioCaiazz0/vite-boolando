<script>

    import {} from '../db.json'; /* QUI??? */ 
    export default{}

</script>

<template>

<section id="products-page">

<div class="container products-container">
        
    <div class="product-page debug">
        <img src="assets/img/1.webp" class="product-image first-image">
        <img src="assets/img/1b.webp" class="product-image second-image">
        <span class="discount"> 50% </span>
        <span class="sustainability"> Sostenibilità </span>
        <span class="saved"> &#9829 </span>
    </div>
       
    <div class="product-info">
        <div class="brand"> Levi's </div>
        <div class="product-name"> RELAXED FIT TEE UNISEX </div>
        <div> 
            <span class="actual-price"> 14,99 &#x20AC </span> 
            <span class="old-price"> 29,99 &#x20AC </span>
        </div>
    </div>

    <div class="product-page debug"> 
        
        <img src="assets/img/2.webp" class="product-image first-image">
        <img src="assets/img/2b.webp" class="product-image second-image">
        <span class="discount"> 30% </span>
        <span class="saved"> &#9829 </span>

        <div class="product-info">
            <div class="brand"> Guess </div>
            <div class="product-name"> ROSES TEE </div>
            <div>
                <span class="actual-price"> 20,99 &#x20AC </span> 
                <span class="old-price"> 29,99 &#x20AC </span>
            </div>
        </div>

    </div>

    <div class="product-page debug"> 
        
        <img src="assets/img/3.webp" class="product-image first-image">
        <img src="assets/img/3b.webp" class="product-image second-image">
        <span class="discount"> 50% </span>
        <span class="sustainability"> Sostenibilità </span>
        <span class="saved"> &#9829 </span>

        <div class="product-info">
            <div class="brand"> Come zucchero filato </div>
            <div class="product-name"> VOGLIA DI COLORI PASTELLO </div>
            <div>
                <span class="actual-price"> 129,99 &#x20AC </span> 
                <span class="old-price"> 184,99 &#x20AC </span>
            </div>
        </div>

    </div>

</div>    

</section>

</template>

<style lang="scss" scoped>

.container.products-container{
    max-width: 1050px;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    position: relative;
}

.product-page{
    display: flex;
    flex-direction: column;
    position: relative;
    max-width: 335px;
    max-height: 530px;
}

.product-image{
    max-width: 335px;
    max-height: 485px;
}

.first-image{
    position: absolute;
    top: 0;
    left: 0;
    z-index: 1;
}

.second-image{
    position: absolute;
    top: 0;
    left: 0;
    z-index: 0;
}

.first-image:hover {
  display: none;
}

.discount{
    position: absolute;
    display: flex;
    top: 430px;
    left: 0;
    color: white;
    height: 20px;
    width: 40px;
    background-color: #ff0001;
    z-index: 2;
    justify-content: center;
    font-size: x-small;
    text-align: center;
    line-height: 20px;
}

.sustainability{
    position: absolute;
    display: flex;
    top: 430px;
    left: 45px;
    color: white;
    height: 20px;
    width: 80px;
    background-color: #038102;
    z-index: 2;
    justify-content: center;
    font-size: x-small;
    text-align: center;
    line-height: 20px;
}

.saved{
    position: absolute;
    display: flex;
    top: 10px;
    right: 0;
    height: 35px;
    width: 35px;
    background-color: white;
    z-index: 2;
    color: black;
    align-items: center;
    justify-content: center;
    font-size: x-large;
}

.product-info{
    display: flex;
    flex-direction: column;
    max-width: 335px;
    max-height: 45px;
    width: 335px;
    height: 45px;
    position: absolute;
    top: 485px;
}

.brand{
    font-size: xx-small;
    color: gray;
}

.product-name{
    font-size: x-small;
    font-weight: bolder;
}

.actual-price{
    color: red;
    font-size: smaller;
    font-weight: bolder;
}

.old-price{
    text-decoration: line-through;
    font-size: smaller;
}

</style>