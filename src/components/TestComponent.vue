<template>
    <div>
        <p>test vue component</p>
        <div class="words">{{testWord}}</div>
    </div>
</template>
<script>
export default {
  name: "testWord",
  props: {
    testWord: {
      type: String
    }
  }
};
</script>
<style scoped>
.words {
  color: brown;
  font-size: 20px;
  padding-top: 50px;
  border: 1px solid green;
  width: 200px;
  height: 60px;
  margin: 0 auto;
}
</style>



