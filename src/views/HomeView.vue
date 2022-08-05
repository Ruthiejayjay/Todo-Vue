<template>
  <div class="container px-7 py-4 mx-auto">
    <HomeHeader />
    <Todos />
    <CompletedTodos />
  </div>
</template>

<script>
// @ is an alias to /src
import HomeHeader from "@/components/HomeHeader.vue";
import Todos from "@/components/Todos.vue";
import CompletedTodos from "@/components/CompletedTodos.vue";
export default {
  name: "HomeView",
  components: {
    HomeHeader,
    Todos,
    CompletedTodos,
  },
};
</script>
