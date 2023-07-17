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
        <section class="footer-links">
          <div class="container">
            <div class="dc-links">
              <ul>
                <h3>
                  DC COMICS
                </h3>
                <li>
                  <a href="#">
                    Characters
                  </a>
                </li>
                <li>
                  <a href="#">
                    Comics
                  </a>
                </li>
                <li>
                  <a href="#">
                    Movies
                  </a>
                </li>
                <li>
                  <a href="#">
                    TV
                  </a>
                </li>
                <li>
                  <a href="#">
                    Games
                  </a>
                </li>
                <li>
                  <a href="#">
                    Videos
                  </a>
                </li>
                <li>
                  <a href="#">
                    News
                  </a>
                </li>
              </ul>
              <ul>
                <h3>
                  DC
                </h3>
                <li>
                  <a href="#">
                    Term of use
                  </a>
                </li>
                <li>
                  <a href="#">
                    Privacy policy (New)
                  </a>
                </li>
                <li>
                  <a href="#">
                    Add Choices
                  </a>
                </li>
                <li>
                  <a href="#">
                    Advertising
                  </a>
                </li>
                <li>
                  <a href="#">
                    Jobs
                  </a>
                </li>
                <li>
                  <a href="#">
                    Subscriptions
                  </a>
                </li>
                <li>
                  <a href="#">
                    Talent workshop
                  </a>
                </li>
                <li>
                  <a href="#">
                    CPSC Certificates
                  </a>
                </li>
                <li>
                  <a href="#">
                    Ratings
                  </a>
                </li>
                <li>
                  <a href="#">
                    Shop Help
                  </a>
                </li>
                <li>
                  <a href="#">
                    Contact us
                  </a>
                </li>
              </ul>
              <ul>
                <h3>
                  SITES
                </h3>
                <li>
                  <a href="#">
                    DC
                  </a>
                </li>
                <li>
                  <a href="#">
                    MAD Magazine
                  </a>
                </li>
                <li>
                  <a href="#">
                    DC Kids
                  </a>
                </li>
                <li>
                  <a href="#">
                    DC Universe
                  </a>
                </li>
                <li>
                  <a href="#">
                    DC Power Visa
                  </a>
                </li>
             </ul>
                

              <ul>
                <h3>
                  SHOP
                </h3>
                <li>
                  <a href="#">
                    Shop DC
                  </a>
                </li>
                <li>
                  <a href="#">
                    Shop DC Collectbles
                  </a>
                </li>
              </ul>
            </div>

            <div class="footer-logo">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>

          </div>
        </section>

        <section class="footer-bottom">
            <div>
                <a href="#">
                    SIGN-UP NOW!
                </a>
            </div>

            <div class="footer-icons">
                
                <a href="#" class="follow">
                    FOLLOW US
                </a>

                <div>
                    <img src="../assets/img/footer-facebook.png" alt="">
                </div>
                <div>
                    <img src="../assets/img/footer-twitter.png" alt="">
                </div>
                <div>
                    <img src="../assets/img/footer-youtube.png" alt="">
                </div>
                <div>
                    <img src="../assets/img/footer-pinterest.png" alt="">
                </div>
                <div>
                    <img src="../assets/img/footer-periscope.png" alt="">
                </div>
                    
               
                    
            </div>
        </section>
          
    </footer>
</template>

       
    
    


<style scoped lang="scss">

.footer-links {
  background-image: url(../assets/img/footer-bg.jpg);
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;

  > .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-top: 100px;
    > .dc-links {
      display: flex;
      flex-wrap: wrap;

      ul {
        width: calc(100% / 3);
        max-height: 160px;
        h3 {
            color: white;
            padding-bottom: 5px;
        }

        li {
            list-style: none;
            a {
                text-decoration: none;
                color:#959595;
                font-size: 12px;
            }
           
        }
      }

      
    }
    > .footer-logo {
        width: 450px;
        
        
      
        > img {
            width: 100%;
            height: 100%;
            
        }
        
       
       
    }
  }

}

.footer-bottom {
    background-color: #303030;
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 70px;

    div {
        // border: 2px solid #1265B2;
        padding: 10px;

        a {
            text-decoration: none;
            color: white;
            padding: 5px;
            text-align: center;
        }
    }

    .footer-icons {
        > .follow {
            color: #1265B2;
            vertical-align: middle;
        }

        div {
            display: inline-block;
            vertical-align: middle;
        }

    }


}


</style>