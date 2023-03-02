<template>
  <div class="page">
    <age-verification v-if="!agree" @agree="()=>agree=true"/>
    <template v-else>
      <my-header/>
      <main-section/>
    </template>
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
}
</style>