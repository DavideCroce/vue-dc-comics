<template>
<div id="main">
    <div class="jumbotron"></div>

    <div id="contents">
      <div class="contain">
          <div class="current-series">
              <button class="c-series">CURRENT SERIES</button>
          </div>
          <Comicslist/>
          <div class="load-button">
              <button class="load">LOAD MORE</button>
          </div>
      </div>
    </div>
    <div id="links-content">
        <LinkContent/>
    </div>
</div>
  
</template>

<script>
import Comicslist from './Comicslist.vue';
import LinkContent from './LinkContent.vue';
export default {
   name: 'Main',
   components:{
       Comicslist,
       LinkContent,
   }
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
        .c-series{
            background-color: dodgerblue;
            padding: 10px;
            color: white;
            width: 200px;
            border: 0;
            font-family: 'PT Sans Narrow', sans-serif;
            font-weight: bold;
            font-size: 20px;
            position: absolute;
            bottom: 2px;
        }
    }
}
#links-content{
    background-color: dodgerblue;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 150px;
}
.load-button{
    display: flex;
    align-items: center;
    justify-content: center;
    padding-top: 20px;
    padding-bottom: 10px;
    .load{
        text-align: center;
        font-family: 'PT Sans Narrow', sans-serif;
        background-color: dodgerblue;
        padding: 10px 50px;
        color: white;
        font-weight: bold;
        border: none;
        font-size: 15px;
    }
}
.jumbotron{
    background-image: url(../assets/img/main-top-bg.jpg);
    background-size: cover;
    height: 400px;
    width: 100%;
}

.current-series{
    position: relative;
}
</style>