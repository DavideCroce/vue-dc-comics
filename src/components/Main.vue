<template>
  <div id="contents">
      <div class="contain">
          <h1 id="content">--<i class="fas fa-chevron-right"></i> Content goes here <i class="fas fa-chevron-left"></i>--</h1>
      </div>
  </div>
</template>

<script>
export default {
   name: 'Main',
}
</script>

<style scoped>
#contents{
    background-color: rgb(19, 19, 19);
    width: 100%;
}

.contain{
    max-width: 1200px;
    margin: 0 auto;
    vertical-align: center;
    padding: 20px 0;
    color: white;

}

</style>