<template>

  <section class="grid md:grid-cols-2 lg:grid-cols-3 grid-cols-1 gap-4 max-w-7xl mx-auto pt-10 pb-10">
    <Card
        image="/mohammed.jpg"
        name="Rogers"
        role="Director"
    />
    <Card
        image="/mohammed.jpg"
        name="Samuel"
        role="Manager"
    />
    <Card
        image="/mohammed.jpg"
        name="Marky"
        role="CEO"
    />
    <Card
        image="/mohammed.jpg"
        name="Christoph"
        role="Public Relation Officer"
    />
    <Card
        image="/mohammed.jpg"
        name="Derrick"
        role="Project Director"
    />
    <Card
        image="/mohammed.jpg"
        name="Nathan"
        role="Chief Executive Officer"
    />

  </section>

</template>
<script>
import Card from '@/components/Card.vue'


export default {
  name: 'App',
  components: { Card }
}

</script>
