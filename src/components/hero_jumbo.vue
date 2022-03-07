<template>
  <div class="jumbo">
    <h3>Un bellissimo Jumbo Pixellato</h3>
  </div>
</template>

<script>
export default {
  name: 'hero_jumbo',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.jumbo{
 background-image: url("../assets/mountains.png");
 height: 400px;
 width:100%;
 background-repeat: no-repeat;
 background-size: cover;
 background-position:center;
 display: flex;
 justify-content: center;
 align-items: center;
 }
 h3{
 font-size: 30px;
 color: rgb(22, 0, 73);
 }
</style>