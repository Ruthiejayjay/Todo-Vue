<template>
  <div class="container flex gap-8 max-w-screen-xl px-7 py-4 mx-auto">
    <div class="w-full">
    <HomeHeader />
    <Todos />
    <CompletedTodos />
    </div>
    <div class="flex flex-col items-center mt-4 md:mt-0">
      <DummyText />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HomeHeader from "@/components/HomeHeader.vue";
import Todos from "@/components/Todos.vue";
import CompletedTodos from "@/components/CompletedTodos.vue";
import DummyText from '@/components/DummyText.vue'
export default {
  name: "HomeView",
  components: {
    HomeHeader,
    Todos,
    CompletedTodos,
    DummyText
  },
};
</script>
