<template>
  <section class="form">
    <q-input class="form__input" dense rounded outlined></q-input>
    <q-btn class='form__add-btn no-shadow' dense no-caps borderless rounded flat>Add</q-btn>
  </section>
</template>

<script lang='ts'>
import {defineComponent} from "vue";
export default defineComponent ({
  name: 'Form'
});
</script>

<style scoped>

</style>
