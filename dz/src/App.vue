<template>
  <p v-if="age <= 18">подросток</p>
  <p v-if="age > 18 && age <= 25">молодой человек</p>
  <p v-if="age > 25">мужчина</p>
</template>

<script>
export default {
  data(){
    return{
      age: +prompt("введите ваш возраст")
    }
  }
}
</script>

<style>

</style>
