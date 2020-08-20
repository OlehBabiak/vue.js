<template>
  <div>
   {{msg}}
   {{2+2}}
   {{isTrue ? 'Yes it`s true' : 'NOO!'}}


  </div>
</template>

<script>


export default {
  name: 'App',

  data(){
    return{
      msg: 'Hello world',
      isTrue: true,

    }
  }
}
</script>

<style>

</style>
