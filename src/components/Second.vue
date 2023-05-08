<template>
    <div id="second">
        <img id="antonella_miranda2" alt="antonella_miranda2" src="@/assets/img/antonella_miranda_6.jpg">
        <img src="@/assets/img/corner2/f1.svg">
        <img src="@/assets/img/corner2/f2.svg">
        <img src="@/assets/img/corner2/f3.svg">
    </div>
</template>

<script>
export default {
    name: 'SecondComponent',
}
</script>

<style lang="scss">

#second {
  position: relative;
  height: 50vh;
  overflow: hidden;
  max-height: 900px;

  img {
    position: absolute;
  }

  #antonella_miranda2 {
    display: block;
    max-width: 1200px;
    margin-left: auto;
    margin-right: auto;
    width: 100%;
  }

}
</style>