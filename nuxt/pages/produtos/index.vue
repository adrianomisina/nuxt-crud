<template>
  <div>
    <div class="bg-gray-100">
      <div class="container mx-auto flex items-center space-x-4 h-10 mb-10">
      <NuxtLink :to="{name: 'a-empresa'}">A empresa</NuxtLink>
      <NuxtLink to="/servicos">Serviços</NuxtLink>
      <NuxtLink to="/produtos">Produtos</NuxtLink>
      </div>
    </div>

    <div>
      <div class="container mx-auto">
        <h1 class="text-lg font-bold mb-6">Produtos</h1>
        <NuxtLink to="/produtos/produto-a">Produto A</NuxtLink>
        <NuxtLink to="/produtos/produto-b">Produto B</NuxtLink>
        <p class="mt-4">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores quod molestias, nisi minima maxime dicta doloremque maiores, voluptatum, explicabo quibusdam blanditiis eius repellendus provident impedit aspernatur nulla alias suscipit veritatis.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  nane: "index",
  data() {
    return{

    }
  }
}
</script>

<style>

</style>