<template>
    <div> Hello {{ person.name }} </div>
    <div> My age is {{ person.age }} </div>
    <div v-if ="person.isDev"> I am dev </div>
    <div v-else> I am not a dev</div>
</template>

<script>
//   // console.log('hello')
// const myVariable = 'hello'
  export default{
      data() {
        return {
          person: {
            name: 'Ben',
            age: 33,
            isDev: false,
         }
        }
      }
}
</script>