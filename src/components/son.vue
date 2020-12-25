<template>
  <ul>
    <li v-for="item in img" :key="item.id">
      <img :src="item.src" alt="" />
    </li>
  </ul>
</template>

<script>
export default {
  props: ["img"],
};
</script>

<style scoped>

ul{
    width: 1200px;
    display: flex;
    list-style: none;
    flex-flow: wrap;
    justify-content: space-around;
    margin: 100px auto;
}
</style>