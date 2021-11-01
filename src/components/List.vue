<template>
  <section>
    <q-list class='todo__list'>
      <q-item class='todo__items'>
        <q-item-label class="todo__name">Buy box for present</q-item-label>
        <q-item-section class="todo__info">
          <q-icon class="todo__icon" name=today size="sm"/>
          <span class="todo__date">01.11.2021</span>
        </q-item-section>
      </q-item>
    </q-list>
  </section>

</template>

<script lang='ts'>
import {defineComponent, ref} from "vue";

export default defineComponent({
  name: 'List'
});
</script>

<style scoped>

</style>
