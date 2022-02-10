<template>
<div id="bg-first" class="h-screen w-screen -z-50 absolute" ></div>
  <h1 class="warning-text absolute w-screen text-center text-4xl uppercase text-yellow-200 font-bold tracking-wider my-7 animate-pulse border-t-8 border-b-8 border-t-amber-300 border-b-amber-300 py-3 pb-4 hover:-tracking-wide cursor-pointer">- Site Under Development -</h1>
</template>

<script>
export default {
  name: "UnderConstruction"
}
</script>

<style scoped>
.warning-text {
  top: 40vh;
}
#bg-first {
  background: #1e272e;
  top: 0;
}
</style>