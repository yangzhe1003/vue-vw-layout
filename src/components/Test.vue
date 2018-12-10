
<template>
  <div class="test">
    {{msg}}
  </div>
</template>

<script>
export default {
  name: "Test",
  data() {
    return {
      msg: "hello viewport"
    } 
  }
};
</script>


<style>
.test {
  width: 750px;
  height: 160px;
  background-color: skyblue;
  font-size: 36px;
}
</style>
