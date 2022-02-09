<template>
  <div class="other-links">
            <div class="links"><img src="../assets/img/buy-comics-digital-comics.png" alt=""><span>DIGITAL COMICS</span> </div>
            <div class="links"><img src="../assets/img/buy-comics-merchandise.png" alt=""><span>DC MERCHANDISE</span> </div>
            <div class="links"><img src="../assets/img/buy-comics-subscriptions.png" alt=""><span>SUBCRIPTION</span> </div>
            <div class="links"><img src="../assets/img/buy-comics-shop-locator.png" alt=""><span>COMIC SHOP LOCATOR</span> </div>
            <div class="links smaller"><img src="../assets/img/buy-dc-power-visa.svg" alt=""><span>DC POWER VISA</span> </div>
    </div>
</template>

<script>
export default {
name: 'LinkContent',
}
</script>

<style scoped lang="scss">
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


.other-links{
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: dodgerblue;
    width: 1200px;
    color: white;
    margin: 0 auto;
}

</style>