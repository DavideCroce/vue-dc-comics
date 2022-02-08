<template>
  <div class="contain">
      <div class="credits">
          <div class="button">
               <button>SIGN-UP NOW!</button>
          </div>
          <div class="socials">
               <h3>FOLLOW US</h3>
               <img src="../assets/img/footer-facebook.png" alt="">
               <img src="../assets/img/footer-twitter.png" alt="">
               <img src="../assets/img/footer-youtube.png" alt="">
               <img src="../assets/img/footer-pinterest.png" alt="">
               <img src="../assets/img/footer-periscope.png" alt="">
          </div>
      </div>
  </div>
</template>

<script>
export default {
   name: 'Credits',
}
</script>

<style scoped>
.contain{
    width: 100%;
    background-color: rgb(51, 51, 51);
    margin: 0 auto;
    height: 100px;
    display: flex;
    justify-content: center;
}
.credits{
    width: 1200px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.socials{
    display: flex;
    align-items: center;
    color: dodgerblue;
}
.socials img{
    height: 30px;
    padding: 0 10px;
}
button{
    background-color: rgb(51, 51, 51);
    padding: 7px 10px;
    color: white;
    border: 2px dodgerblue solid;
    font-family: 'PT Sans Narrow', sans-serif;
    font-size: 17px;
    font-weight: bold;
}
</style>