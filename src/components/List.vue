<template>



  <div>
      <h5 @click="$router.push('/detail/0')">{{ 블로그글[0].title }}</h5>
      <p>{{ 블로그글[0].date }}</p>
  </div>
  <div>
      <h5>{{ 블로그글[1].title }}</h5>
      <p>{{ 블로그글[1].date }}</p>
  </div>
  <div>
      <h5>{{ 블로그글[2].title }}</h5>
      <p>{{ 블로그글[2].date }}</p>
  </div>

    <!-- <div v-for="i in 블로그글" :key="i">
        <h5 @click="$router.push('/detail/0')">{{ i.title }}</h5>
        <p>{{ i.date }}</p>
    </div> -->




</template>

<script>
export default {
    name : 'List',
    props : {
        블로그글 : Array,
    }
}
</script>

<style>

</style>