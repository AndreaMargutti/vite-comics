<script>
import AppCardsList from './AppCardsList.vue';
export default {
  data() {
    return {
      
    }
  },
  components: {
    AppCardsList
  }
}
</script>

<template>
    <main>
      <div class="container">
        <AppCardsList />
      </div>
    </main>
</template>

<style lang="scss" scoped>
  @use "../style/general.scss" as *;

  main {
    background-color: #1C1C1C;
    color: white;
    height: 150px;
    padding: 60px 0;
    p {
      vertical-align:middle;
      font-weight: bolder;
      font-size: 2rem;
    }
  }
</style>