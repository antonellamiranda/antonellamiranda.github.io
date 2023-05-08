<template>
  <div class="page">
    <age-verification v-if="!agree" @agree="()=>agree=true"/>
    <main-view v-else/>
  </div>
</template>

<script>


export default {
  name: 'IndexPage',
  data() {
    return {
      agree: false
    }
  }
}
</script>

<style lang="scss">
.page {
  height: 100%;
  background-color: #f66c6c;
  //background-color: #FF0000;
}
</style>