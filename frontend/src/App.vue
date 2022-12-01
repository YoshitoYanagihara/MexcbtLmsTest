<script setup lang="ts">
import LmsApi from "@/modules/LmsApi"

const apiTest = async () => {
  const response = await LmsApi.post("/LmsLogin")
  console.log(response)
}
</script>

<template lang="pug">
button(@click="apiTest") Test
</template>

<style lang="sass" scoped>
</style>
