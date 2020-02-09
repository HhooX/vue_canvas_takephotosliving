<template>
  <div class="hello">
    <takephoto/>
  </div>
</template>

<script>
import takephoto from './takephoto'
export default {
  name: "HelloWorld",
  components:{
    takephoto
  },
  data() {
    return {};
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
@import "@/styles/global.scss";
.hello {
  display: flex;
  flex-flow: column;
  justify-content: flex-start;
  align-items: flex-start;
  width: vw(1920);
  height: vh(1080);
  overflow: hidden;
}
a {
  color: #42b983;
  color: #2c3e50;
}
</style>
