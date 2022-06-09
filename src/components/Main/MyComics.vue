<template>
    <div class="comic">
      <img :src="details.thumb" :alt="details.series">
      <h5>{{ details.series }}</h5>
    </div>
</template>

<script>
export default {
  name: 'MyComics',
  props: {
    details: Object
  }
}
</script>

<style scoped lang="scss">
.comic {
  margin: 10px;
  // flex-basis: 20%;
  width: 15%;

  img {
    width: 100%;
  }

  h5 {
    color: white;
  }
}
</style>