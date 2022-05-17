<template>
  <div v-for="item in items" :key="item.id">
  <h1> {{item}}</h1>
  </div>
</template>

<script>
export default {

 data () {
   return {
     items: [
       {
       id: 1,
       name: 'ulol'
       }
     ]
   }
 }
}

</script>