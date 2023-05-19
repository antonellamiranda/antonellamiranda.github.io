<template>
  <div id="first">
    <div class="container">
      <img
        id="antonella_miranda"
        alt="antonella_miranda"
        src="@/assets/img/antonella_miranda_4.jpg"
      />
      <img id="corner" alt="corner" src="@/assets/img/corner1/f.svg" />
      <!--      <span id="name1">Antonella</span>-->
      <!--      <span id="name2">Miranda</span>-->
    </div>
  </div>
</template>

<script>
export default {
  name: 'FirstComponent',
}
</script>

<style lang="scss">
#first {
  background-color: blue; //Debug
  .container {
    position: relative;
    background-color: aqua; //Debug
    max-width: 1366px;
    margin-right: auto;
    margin-left: auto;
  }

  img {
    //position: absolute;
  }

  #name1 {
    font-size: 5.5rem;
    position: absolute;
    left: 1rem;
  }

  #name2 {
    font-size: 4.5rem;
    position: absolute;
    left: 1rem;
    top: 6rem;
  }

  #corner {
    width: 85%;
    position: absolute;
    left: 0;
  }

  #antonella_miranda {
    width: 100%;
  }

  //position: relative;
  //height: 50vh;
  //overflow: hidden;
  //max-height: 900px;
  //
  //img {
  //  position: absolute;
  //}
  //
  //#antonella_miranda {
  //  display: block;
  //  max-width: 1200px;
  //  margin-left: auto;
  //  margin-right: auto;
  //  width: 100%;
  //}
}
</style>
