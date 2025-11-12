<template>
  <p class=" text-xl text-center text-black/40">{{ role }}</p>
</template>
<script>
export default {
  name: "CardRole",
  props: {
    role: {
      type: String,
      required: true
    }
  }
}
</script>