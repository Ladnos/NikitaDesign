<script setup lang="ts">
import About from './components/About.vue';
import Header from './components/Header.vue';
import MainPage from './components/MainPage.vue';
import Problems from './components/Problems.vue';
import Quirks from './components/Quirks.vue';
import Separator from './components/ui/separator/Separator.vue';

</script>

<template>
  <div class=" space-y-10 px-2">
    <Header></Header>
    <MainPage></MainPage>
    <Separator></Separator>
    <About></About>
    <Separator></Separator>
    <Quirks></Quirks>
    <Separator></Separator>
    <Problems></Problems>
    <Separator></Separator>
    <footer class="lg:w-1/2 w-full mx-auto text-center text-muted-foreground py-8">
      <p>разработано студией Бодрые Котлы для меня</p>
    </footer>
  </div>
</template>

<style scoped></style>
