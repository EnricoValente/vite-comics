<script>
    export default {
    data() {
      return {
        
      }
    }
  }
</script>


<template>
    <header>
		<div class="container">
			<div>
				<img src="../assets/img/dc-logo.png" alt="">
			</div>
			
			<ul>
			  <li>
				<a href="#">
					CHARACTERS
				</a>
			  </li>
			  <li>
				<a href="#" class="active">
					COMICS
				  </a>
			  </li>
			  <li>
				<a href="#">
					MOVIES
				</a>
			  </li>
			  <li>
				<a href="#">
					TV
				</a>
			  </li>
			  <li>
				<a href="#">
					GAMES
				</a>
			  </li>
			  <li>
				<a href="#">
					COLLECTIBLES
				</a>
			  </li>
			  <li>
				<a href="#">
					VIDEOS
				</a>
			  </li>
			  <li>
				<a href="#">
					FANS
				</a>
			  </li>
			  <li>
				<a href="#">
					NEWS
				</a>
			  </li>
			  <li>
				<a href="#">
					SHOP
				</a>
			  </li>
			</ul>
		</div>
    </header>
</template>
    


<style scoped lang="scss">
    header {
	  background-color: white;

	  > .container {
		display: flex;
		justify-content: space-between;
		padding: 30px 0;
	  }
	
		ul{
		
			display: flex;
			align-items: center;

			li {
				list-style: none;

				
				a {
					text-decoration: none;
					color: black;
					font-size: 12px;
					padding: 10px;

					&.active {
		              color:  #0282F9;
					
					}
				}

			}
		
		}
   }


</style>