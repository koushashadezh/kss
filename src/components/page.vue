<template>
  <div class="page">
    <one></one>
    <two></two>
  </div>
</template>

<script>
import one from './one';
import two from './two';
export default {
    'name': 'page',
    'components': {
        one,
        two,
    },
    data() {
        return {};
    }
};
</script>


<style scoped>
.page {
  width: 5000px;
  /* height: 150px; */
  background-color: blanchedalmond;
  margin: auto;
  /* border-radius: 10px; */
  /* margin-top: 30px; */
}
.one{
  text-align: center
}
</style>