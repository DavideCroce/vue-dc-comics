<template>
<div id="main">
    <div id="contents">
      <div class="contain">
          <h1 id="content">- -<i class="fas fa-chevron-right"></i> Content goes here <i class="fas fa-chevron-left"></i>- -</h1>
      </div>
    </div>
    <div id="links-content">
       <div class="other-links">
            <div class="links"><img src="../assets/img/buy-comics-digital-comics.png" alt=""><span>DIGITAL COMICS</span> </div>
            <div class="links"><img src="../assets/img/buy-comics-merchandise.png" alt=""><span>DC MERCHANDISE</span> </div>
            <div class="links"><img src="../assets/img/buy-comics-subscriptions.png" alt=""><span>SUBCRIPTION</span> </div>
            <div class="links"><img src="../assets/img/buy-comics-shop-locator.png" alt=""><span>COMIC SHOP LOCATOR</span> </div>
            <div class="links smaller"><img src="../assets/img/buy-dc-power-visa.svg" alt=""><span>DC POWER VISA</span> </div>
      </div>
    </div>
</div>
  
</template>

<script>
export default {
   name: 'Main',
}
</script>

<style scoped lang="scss">
#main{
    width: 100%;
    z-index: 1;
}
#contents{
    background-color: rgb(19, 19, 19);
    width: 100%;
    .contain{
        max-width: 1200px;
        margin: 0 auto;
        vertical-align: center;
        padding: 20px 0;
        color: white;
    }
}

.links{
    /* margin: 0 20px; */
    display: flex;
    justify-content: center;
    align-items: center;
    img{
        height: 45px;
        padding: 0 10px;
    }
}

.smaller img{
    height: 30px;
}

#links-content{
    background-color: dodgerblue;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 150px;

    .other-links{
        display: flex;
        justify-content: space-between;
        align-items: center;
        background-color: dodgerblue;
        width: 1200px;
        color: white;
        margin: 0 auto;
    }
}
</style>