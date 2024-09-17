<script>
import CardsList from './CardsList.vue';

export default {
  data() {
    return {
      
    }
  },

  components: {
    CardsList
  }
}
</script>

<template>
    <main>
      <div class="container">
        <CardsList />
      </div>
    </main>
</template>

<style lang="scss" scoped>
  @use "../style/general.scss" as *;

  main {
    background-color: #1C1C1C;
    color: white;
    padding: 60px 0;
    p {
      vertical-align:middle;
      font-weight: bolder;
      font-size: 2rem;
    }
  }
</style>