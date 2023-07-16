<script>
    export default {
    data() {
      return {
        
      }
    }
  }
</script>


<template>
    <main>
      <section class="content">
        <div class="container">
          <h1>
            Content goes here
          </h1>
        </div>
      </section>

      <section class="buy-links">
        <ul>
          <li>
            <span>
              <div>
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
              </div>
              <a href="#">
                DIGITAL COMICS
              </a>
            </span>

          </li>
          <li>
            <span>
              <div>
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
              </div>
              <a href="#">
                DC MERCHANDISE
              </a>
            </span>
          </li>
          <li>
            <span>
              <div>
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
              </div>
              <a href="#">
                SUBSCRIPTON
              </a>
            </span>
          </li>
          <li>
            <span>
              <div>
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
              </div>
              <a href="#">
                COMIC SHOP LOCATOR
              </a>
            </span>
          </li>
          <li>
            <span>
              <div>
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
              </div>
              <a href="#">
                DC POWER VISA
              </a>
            </span>
          </li>
        </ul>

      </section>
        
    </main>
</template>

       
    
    


<style scoped lang="scss">
  main {
    > .content {
      padding: 50px 0;
      
      h1 {
        color: white;
      }
    }
    background-color: black;

    > .buy-links {
      background-color:#0282F9;

      ul {
        display: flex;
        align-items: center;
        justify-content: center;

        li {
          list-style: none;
          padding: 30px;
          
          > span {
            display: flex;
            align-items: center;
            

            > div {
              width: 60px;
            }
          }
          
          img {
            width: 100%;
            object-fit: cover;
          }

          a {
            text-decoration: none;
            color: white;
            font-size: 12px;
            padding-left: 20px;
          }
          
        }
      }
    }
  }


</style>