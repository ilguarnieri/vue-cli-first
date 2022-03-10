<template>
  <div class="jumbo">
    <img src="https://picsum.photos/1000/500" alt="lorem">
    <h2 class="jumbo-title">Lorem ipsum</h2>
  </div>
</template>

<script>
export default {
  name: 'JumboTron'
}
</script>


<style scoped lang="scss">
.jumbo{
  border-radius: 20px;
  overflow: hidden;
  position: relative;
}

.jumbo-title{
  position: absolute;
  bottom: 20px;
  right: 20px;
  color: white;
}

</style>
