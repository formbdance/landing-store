<script setup>
import { RouterLink } from 'vue-router'
import ShoppingCart from '@/entity/corsine/ShoppingCart.vue'
</script>

<template>
  <header class="container mt-6 m-auto " style="max-width: 1128px;">
    <nav class="flex w-full justify-between items-center " style="font-size: 15px;" >
      <div class="flex justify-between w-1/3 items-center">
        <RouterLink to="/"><p >Для мужчин</p></RouterLink>
        <RouterLink to="/about"><p >Для женщин</p></RouterLink>
        <RouterLink to="/about"><p >Для детей</p></RouterLink>
      </div>
      <h3 class="font-bold flex gap-6" style="font-size: 24px;">
        <img src="../assets/logo.png"/>
        THE LOOP
      </h3>
      <div class="flex w-1/3 justify-between items-center">
        <RouterLink to="/"><p >Оплата</p></RouterLink>
      <RouterLink to="/about"><p >Доставка</p></RouterLink>
      <RouterLink to="/about"><ShoppingCart /></RouterLink>
      </div>
    </nav>

  </header>
</template>


