<template>
  <div v-for="i in 블로그글" :key="i">
      <h5>{{ i.title }}</h5>
      <p>{{ i.content }}</p>
  </div>
</template>

<script>
export default {
    name : 'Detail',
    props : {
        블로그글 : Array,
    }
}
</script>

<style>

</style>