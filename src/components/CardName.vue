<template>
  <h1 class="font-bold text-3xl text-center uppercase">{{ name }}</h1>
</template>

<script>
export default {
  name: 'CardName',
  props: {
    name: {
      type: String,
      required: true
    }
  }
}
</script>