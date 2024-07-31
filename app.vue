<template>
  <div>
    <NuxtRouteAnnouncer />
    <NuxtWelcome />
    <Card />
  </div>
</template>


<script setup lang="ts">
import Card from "@/components/Card.vue"
import { a } from "./index"
console.log(a);

</script>