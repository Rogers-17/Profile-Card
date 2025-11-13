<template>

  <section class="grid md:grid-cols-2 lg:grid-cols-3 grid-cols-1 gap-4 max-w-7xl mx-auto pt-10 pb-10">
    <Card
        image="/mohammed.jpg"
        name="Rogers"
        role="Director"
    />
    <Card
        image="/picture1.jpg"
        name="Samuel"
        role="Manager"
    />
    <Card
        image="/picture2.JPG"
        name="Marky"
        role="CEO"
    />
    <Card
        image="/picture3.JPG"
        name="Christoph"
        role="Public Relation Officer"
    />
    <Card
        image="/picture4.JPG"
        name="Derrick"
        role="Project Director"
    />
    <Card
        image="/picture5.JPG"
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
