<script>
export default {
  data() {
    return {
      navList: [
        "characters",
        "comics",
        "movies",
        "tv",
        "games",
        "collectibles",
        "videos",
        "fans",
        "news",
        "shop"
      ]
    }
  }
}
</script>

<template>
    <header class="container">
        <nav>
            <img src="../assets/img/dc-logo.png" alt="">
            <ul>
                <li v-for="navItem in navList">
                  {{ navItem.toUpperCase() }}
                </li>
            </ul>
        </nav>
    </header>
</template>

<style lang="scss" scoped>
    @use "../style/general.scss" as *;

    nav {
      padding: 20px 0;
      background-color: white;
      display: flex;
      justify-content: space-between;
      text-align: center;
      ul {
        display: flex;
        justify-content:space-between;
        align-items: center;
        li{
          list-style-type: none;
          padding: 10px;
          font-weight: bolder;
        }
      }
    }
</style>