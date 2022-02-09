<template>
  <div class="contain">
      <div class="links">
          <div class="comics-shop">
                <ul>
                    <h3>DC COMICS</h3>
                    <li>Charachters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>Tv</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
                <ul>
                    <li><h3>SHOP</h3></li>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
            </div>
            <div class="dc">
                <ul>
                    <li><h3>DC</h3></li>
                    <li>Terms Of Use</li>
                    <li>Privacy Policy (New)</li>
                    <li>Ad Choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                    <li>Talent Workshops</li>
                </ul>
            </div>
            <div class="sites">
                <ul>
                    <li><h3>SITES</h3></li>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
            </div>
        </div>
        <div class="dclogo"></div>
  </div>
</template>

<script>
export default {
  name: 'Footer',
}
</script>

<style scoped lang="scss">
ul{
    list-style-type: none;
    padding: 0;
}
.links{
    display: flex;
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px 0;
    div{
        padding: 0 15px;
    }
}
.contain{
    width: 100%;
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    color: rgb(141, 140, 140);
    display: flex;
    align-items: center;
    height: 350px;
    .links{
        display: flex;
        max-width: 1200px;
        margin: 0 auto;
        padding: 20px 0;
        div{
            padding: 0 15px;
        }
    }
}

h3{
    color: white;
    padding: 5px 0;
}
.dclogo{
    background-image: url(../assets/img/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-size: cover;
    height: 350px;
    width: 30%;
    background-position-y: center;
    margin-right: 300px;
}
</style>