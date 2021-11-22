<template>
  <div>
    <!-- Hero Section -->
    <hero />
    <!-- Hero Section -->
    <section class="section">
      <div class="container">
        <h1 class="title">Featured Courses</h1>
        <div class="columns">
          <div class="column is-one-quarter">
            <!-- CARD-ITEM -->
            <course-card/>
            <!-- CARD-ITEM-END -->
          </div>
        </div>
      </div>
    </section>
    <section class="section">
      <div class="container">
        <h1 class="title">Featured Articles</h1>
        <div class="columns">
          <div class="column is-one-quarter">
            <!-- CARD-ITEM -->
            <block-card/>
            <!-- CARD-ITEM-END -->
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Hero from '~/components/shared/Hero.vue'
import CourseCard from '~/components/CourseCard.vue'
import BlockCard from '~/components/BlockCard.vue'

export default {
  components: {
    Hero,
    CourseCard,
    BlockCard
  }
}
</script>

<style scoped lang="scss">
  // Home page
  .links {
    padding-top: 15px;
  }
</style>