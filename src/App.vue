<template>
  <div>
    <son :img="list" />
  </div>
</template>

<script>
import son from "./components/son";
// import axios from "axios";
export default {
  components: {
    son,
  },
  data() {
    return {
      list: [
        { id: 1, src: require("./assets/img/1.jpg") },
        { id: 2, src: require("./assets/img/2.jpg") },
        { id: 3, src: require("./assets/img/3.jpg") },
        { id: 4, src: require("./assets/img/4.jpg") },
        { id: 5, src: require("./assets/img/5.jpg") },
        { id: 6, src: require("./assets/img/6.jpg") },
        { id: 7, src: require("./assets/img/7.png") },
        { id: 8, src: require("./assets/img/8.png") },
      ],
    };
  },
  // created() {
  //   axios
  //     .get(
  //       "https://www.fastmock.site/mock/4f60d566644d6646e94d679ea86f9287/aixue8/zpq"
  //     )
  //     .then((res) => {
  //       console.log(res.data.list);
  //       this.list = res.data.list;
  //     });
  // },
};
</script>

<style  scoped>
</style>