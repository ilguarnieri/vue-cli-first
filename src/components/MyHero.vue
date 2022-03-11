<template>
  <div class="jumbo">
    <div  class="jumbo-title">
      <h2>Lorem ipsum</h2>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MyHero'
}
</script>


<style scoped lang="scss">
.jumbo{
  max-width: 1440px;
  height: 400px;
  margin: 0 auto;
  position: relative;
  background-image: url('https://picsum.photos/1200/500');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  overflow: hidden;
}

.jumbo-title{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background-color: rgba(0,0,0,0.4);
  color: white;
  padding: 20px 50px;
  white-space: nowrap;
  border-radius: 8px;
}

</style>
