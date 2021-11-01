<template>
  <q-page class="page">
    <main class='page__main'>
      <h1 class='page__title'>Jobs to Done</h1>
      <Form class='page__form'></Form>
      <List class='page__list'></List>
    </main>
  </q-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import Form from 'components/Form.vue';
import List from 'components/List.vue';

export default defineComponent({
  name: 'PageIndex',
  components: {  Form, List },
  setup() {
    return { };
  }
});
</script>
