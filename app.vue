<template>
  <div>
    <p>home</p>
    {{ data }}
  </div>
</template>

<script setup>
const data = await GqlCharacters();
</script>
