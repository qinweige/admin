<template>
  <section class="todoapp">
    <todo-card :card-title="cardTitle1"></todo-card>
    <todo-card :card-title="cardTitle2"></todo-card>
    <todo-card :card-title="cardTitle3"></todo-card>
  </section>
</template>

<script>
import TodoCard from './TodoCard.vue'


export default {
  components: { TodoCard },
  data() {
    return {
      cardTitle1: 'the day',
      cardTitle2: 'the week',
      cardTitle3: 'the month',
    }
  }
}
</script>

<style lang="scss">
  @import './index.scss';
</style>
