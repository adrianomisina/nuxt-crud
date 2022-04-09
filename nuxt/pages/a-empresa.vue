<template>
  <div>
    <div class="bg-gray-100">
      <div class="container mx-auto flex items-center space-x-4 h-10 mb-10">
        <NuxtLink :to="{name: 'a-empresa'}">A empresa</NuxtLink>
        <NuxtLink to="/servicos">Serviços</NuxtLink>
      </div>
    </div>

    <div>
      <div class="container mx-auto">
        <h1 class="text-lg font-bold">A empresa</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores quod molestias, nisi minima maxime dicta doloremque maiores, voluptatum, explicabo quibusdam blanditiis eius repellendus provident impedit aspernatur nulla alias suscipit veritatis.</p>
      </div>
    </div>

  </div>
</template>

<script>
name:'a-empresa'
export default {
  data() {
    return {

    }
  }
}
</script>

<style>

</style>