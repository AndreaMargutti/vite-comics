<script>
export default {
  data() {
    return {
      
    }
  }
}
</script>

<template>
    <footer>
      <div class="container">
        <section class="d-flex">
            <ul>
              <li><h5>DC COMICS</h5></li>
              <li>Characters</li>
              <li>Comics</li>
              <li>Movies</li>
              <li>TV</li>
              <li>Games</li>
              <li>Videos</li>
              <li>News</li>
            </ul>
            <ul>
              <li><h5>DC</h5></li>
              <li>Terms of Use</li>
              <li>Privacy Police (New)</li>
              <li>Ad Choices</li>
              <li>Advertising</li>
              <li>Jobs</li>
              <li>Subscriptions</li>
              <li>Talent Workshop</li>
              <li>CPSC Certificates</li>
              <li>Ratings</li>
              <li>Shop Help</li>
              <li>Contact Us</li>
            </ul>
            <ul>
              <li><h5>SITES</h5></li>
              <li>DC</li>
              <li>MAD Magazine</li>
              <li>DC Kids</li>
              <li>DC Universe</li>
              <li>DC Power Visa</li>
            </ul>
            <ul>
              <li><h5>SHOP</h5></li>
              <li>Shop DC</li>
              <li>Shop DC Collectibles</li>
            </ul>
          </section>
        <section>
          <img src="../assets/img/dc-logo-bg.png" alt="">
        </section>
      </div>
    </footer>
</template>

<style lang="scss" scoped>
    @use "../style/general.scss" as *;
    
    footer {
      background-image: url(../assets/img/footer-bg.jpg);
      background-repeat: no-repeat;
      background-size: cover;
      div {
        display: flex;
        section {
          flex-basis: 50%;
        }
      }
      ul {
        font-weight: bolder;
        list-style-type: none;
        padding: 10px;
        li {
          color: #959595;
          margin-bottom: 5px;
          h5 {
            color: white;
            font-size: 1.2rem;
          }
        }
      }
    }

    .d-flex {
      display: flex;
      flex-wrap: wrap;
    }
    </style>