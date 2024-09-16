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
    <header>
        <nav>
            <img src="../assets/img/dc-logo.png" alt="">
            <ul>
                <li v-for="navItem in navList">
                  {{ navItem }}
                </li>
            </ul>
        </nav>
    </header>
</template>

<style lang="scss" scoped>
    nav {
      background-color: white;
      display: flex;
      justify-content: space-around;
      text-align: center;
      padding: 20px;
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