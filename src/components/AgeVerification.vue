<template>
  <div class="cover">
    <div class="box">
      <h2>Age Verification</h2>

      <h4>Adult content. You must be 18 or over to access this site. If you are under 18 then must leave.</h4>

      <div class="buttons">
        <button @click="leave">No, I'm under 18</button>
        <button @click="agree" class="primary">Yes, I'm 18</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AgeVerification',
  methods: {
    leave() {
      window.location.assign('https://www.google.com/search?q=cartoons&tbm=isch');
    }, agree() {
      this.$emit("agree");
    }
  }
}
</script>

<style lang="scss">

$colorA: #FF14A4;
$colorB: #E312D4;
$colorC: #DE21FA;
$colorD: #A312E3;
$colorE: #8C14FB;

$C1: #FBABDC;
$C2: #F95EBE;
$C3: #C74C98;
$C4: #7A2F5D;
$C5: #7A536B;

.cover {
  display: flex;
  justify-content: center;
  align-items: center;

  background-color: $C5;
  height: 100%;
  width: 100%;
}

.box {
  display: flex;
  flex-direction: column;
  align-items: center;

  background-color: $C1;
  color: $C4;

  padding: 1rem;
  border-radius: 1rem;
  border: $C2 solid 3px;


  width: 95%;
  @media (min-width: 480px) {
    //iPads, Tablets
    width: 70%;
  }
}

.buttons {
  margin-top: 2rem;

  button {
    background-color: $C1;
    color: $C4;
    border: $C4 solid 3px;

    &.primary {
      color: $C3;
      border: $C3 solid 3px;
    }

    &:hover {
      opacity: 0.5;
      cursor: pointer;
    }
  }
}
</style>