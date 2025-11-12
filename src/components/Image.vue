<template>
  <img :src="src" alt="avatar" class="h-40 rounded-full shadow-2xl object-cover object-center mt-[-60px]">
</template>
<script>
export default {
  name: 'CardImage',
  props: {
    src: {
      type: String,
      required: true
    }
  }
}
</script>