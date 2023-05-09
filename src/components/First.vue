<template>
    <div id="first">
        <div class="container">
            <img id="antonella_miranda" alt="antonella_miranda" src="@/assets/img/antonella_miranda_4.jpg">
            <img src="@/assets/img/corner1/f1.svg">
            <img src="@/assets/img/corner1/f2.svg">
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
    background-color: aqua; //Debug
    max-width: 1366px;
    margin-right: auto;
    margin-left: auto;

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