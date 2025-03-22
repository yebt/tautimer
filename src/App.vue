<script setup lang="ts">
// import { ref } from "vue";
//
// const name = ref('tomas')
</script>

<template>
  <main class="container mx-auto">
    <nav class="flex flex-col gap-1 mx-auto">
      <ul>
        <li>
          <router-link :to="{ name: 'home' }"> Home </router-link>
        </li>
        <li>
          <router-link :to="{ name: 'about' }"> About </router-link>
        </li>
      </ul>
    </nav>

    <section>Main content section</section>
    <header>
      <router-view></router-view>
    </header>
    <!-- <input type="text"  v-model="name"> -->
    <!--  -->
    <!-- <label >{{ name }}</label> -->
  </main>
</template>

<style scoped>
a {
  text-decoration: underline;
}
</style>
