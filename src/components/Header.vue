<template>
  <div id="hdr">
      <figure>
          <img src="../assets/img/dc-logo.png" alt="">
      </figure>
      <nav>
          <ul>
              <li><a href="#">CHACRACTERS</a></li>
              <li><a href="#">COMICS</a></li>
              <li><a href="#">MOVIES</a></li>
              <li><a href="#">TV</a></li>
              <li><a href="#">GAMES</a></li>
              <li><a href="#">COLLECTIBLES</a></li>
              <li><a href="#">VIDEOS</a></li>
              <li><a href="#">FANS</a></li>
              <li><a href="#">NEWS</a></li>
              <li><a href="#">SHOP</a></li>
          </ul>
      </nav>
  </div>
</template>

<script>
export default {
 name: 'Header',
}
</script>

<style scoped>
#hdr{
    max-width: 1200px;
    height: 100px;
    display: flex;
    margin: 0 auto;
    justify-content: space-between;
    align-items: center;
}

li{
    list-style-type: none;
    padding: 0 20px;
}

ul{
    display: flex;
    justify-content: center;
    align-items: center;
}

a{
    color: black;
    text-decoration: none;
    padding: 50px 0;
    font-weight: 900;
    font-size: 14px;
}

a:hover{
    color: dodgerblue;
    border-bottom: solid dodgerblue 5px;
}
img{
    height: 70px;
}

</style>