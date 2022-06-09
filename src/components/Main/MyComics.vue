<template>
  <div>
    <div class="comic">
      <img :src="details.thumb" :alt="details.series">
      <h5>{{ details.series }}</h5>
    </div>
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

<style>
.comic {
  margin: 10px;
  width: 15%;

  img {
    width: 100%;
  }

  h5 {
    color: white;
  }
}
</style>