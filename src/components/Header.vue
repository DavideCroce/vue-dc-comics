<template>
  <div id="hdr">
      <figure>
          <img src="../assets/img/dc-logo.png" alt="">
      </figure>
      <nav>
          <ul>
              <li  v-for="link in links" :key="link"><a :href="`${link.url}`">{{link.text}}</a></li>
          </ul>
      </nav>
  </div>
</template>

<script>
export default {
 name: 'Header',
 data(){
    return{
    links:
    [
        {
            text:'CHARACTERS',
            url: '#',
        },
        {
            text:'COMICS',
            url: '#',
        },
        {
            text:'MOVIES',
            url: '#',
        },
        {
            text:'TV',
            url: '#',
        },
        {
            text:'GAMES',
            url: '#',
        },
        {
            text:'COLLECTIBLES',
            url: '#',
        },
        {
            text:'VIDEOS',
            url: '#',
        },
        {
            text:'FANS',
            url: '#',
        },
        {
            text:'NEWS',
            url: '#',
        },
        {
            text:'SHOP',
            url: '#',
        },
    ],
    };
    
 }
}
</script>

<style scoped lang="scss">
#hdr{
    max-width: 1200px;
    height: 100px;
    display: flex;
    margin: 0 auto;
    justify-content: space-between;
    align-items: center;
    z-index: 1;
}


ul{
    display: flex;
    justify-content: center;
    align-items: center;
    li{
        list-style-type: none;
        padding: 0 20px;
        a{
            color: black;
            text-decoration: none;
            padding: 35px 0;
            font-weight: 900;
            font-size: 14px;
            &:hover{
                color: dodgerblue;
                border-bottom: solid dodgerblue 5px;
                cursor: pointer;
            }
        }
    }
}

img{
    height: 70px;
}

</style>