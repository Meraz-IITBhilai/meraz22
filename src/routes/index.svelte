<script>
	import Hero from './_Hero.svelte';
	import 'lite-youtube-embed/src/lite-yt-embed.css';
</script>

<svelte:head>
	<title>Meraz '22</title>
</svelte:head>

<div style="background-color:white">
<div class="section">

	<!-- <h1>Meraz 22</h1> -->

	<div class="video-container">
		<div class="color-overlay"></div>
		<video class="vidd" autoplay loop muted>
			<source src="assets/bggg.mp4" type="video/mp4">
		</video>
	</div>
	<img style="display: inline-block" class="newmeraz" src="assets/newmeraz.png" alt="" srcset="">
	<button class="btn third">Register</button>
</div>

<!-- <div class="section1">
    
</div>
<div style="height:200px">
  <video  autoplay loop muted>
    <source src="assets/bggg.mp4" type="video/mp4">
  </video>
</div> -->
<div class="section1">
  <!-- <img class = "bg3" src="/assets/bg3.png" alt="" srcset=""> -->
  <p class="text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.<br>
    Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. <br>
    Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. <br>
    Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. 
  </p>
  <video  class="video" autoplay loop muted>
      <source src="assets/LostStories.mp4" type="video/mp4">
    </video>    
</div>


<div class="section2">
  <video  class="video1" autoplay loop muted>
    <source src="assets/Neophilis.mp4" type="video/mp4">
  </video> 
  <p class="text1">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.<br>
    Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. <br>
    Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. <br>
    Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. 
  </p>   
</div>
<div class="section3">
  <video  class="video2" autoplay loop muted>
    <source src="assets/vipul.mp4" type="video/mp4">
  </video> 
  <p class="text2">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.<br>
    Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. <br>
    Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. <br>
    Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. 
  </p>   
</div>
<div class="section2">
  <video  class="video1" autoplay loop muted>
    <source src="assets/Neophilis.mp4" type="video/mp4">
  </video> 
  <p class="text1">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.<br>
    Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. <br>
    Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. <br>
    Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. 
  </p>   
</div>
<div class="section3">
  <video  class="video2" autoplay loop muted>
    <source src="assets/vipul.mp4" type="video/mp4">
  </video> 
  <p class="text2">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.<br>
    Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. <br>
    Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. <br>
    Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. 
  </p>   
</div>
<div class="section2">
  <video  class="video1" autoplay loop muted>
    <source src="assets/Neophilis.mp4" type="video/mp4">
  </video> 
  <p class="text1">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.<br>
    Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. <br>
    Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. <br>
    Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. 
  </p>   
</div>
</div>
  <!-- <Hero /> -->
<!-- <div class="full">
<Hero />
<section class='glimpses'>
	<div class="title">
	<h1 style='font-weight: normal'>Meraz'22 Teaser</h1>
	</div>
	<iframe src="https://www.youtube.com/embed/W0VIHUbZ680" title="" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</section>



<section class='glimpses'>
	<div class="title">
	<h1 style='font-weight: normal'>Meraz'19 Glimpses</h1>
	</div>
	<iframe src="https://www.youtube.com/embed/fjtuMhY1KK8" title="" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</section>

<section class='glimpses'>
	<div class="title">
	<h1 style='font-weight: normal'>Meraz'18 Glimpses</h1>
	</div>
	<iframe  src="https://www.youtube.com/embed/uOQbTb4-ejs" title="" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</section>
</div> -->

<style lang="scss">
  .vidd{
    transform: translate(-7.5%);
  }
  .video{
    position:absolute;
    width:620px;
    height:100%;
    left:5%;
  }
  .video1{
    position:absolute;
    width:620px;
    height:100%;
    right:5%  ;
  }
  .video2{
    position:absolute;
    width:620px;
    height:100%;
    left:5%;
  }
  .text{
    position: absolute;
    color: white;
    top:250px;
    right:0px;
    width: 40%;
    height: 100%;
    align-items: center;
  }
  .text1{
    position: absolute;
    color: black;
    top:100px;
    left:0px;
    width: 40%;
    height: 100%;
    align-items: center;
  }
  .text2{
    position: absolute;
    color: white;
    top:250px;
    right:0px;
    width: 40%;
    height: 100%;
    align-items: center;
  }
  

// 	.full {
// 		background-color: #040406;
// 	}
// 	section {
// 		height: 100vh;
// 		// padding-top: 75px;
// 		scroll-snap-align: start;
// 		scroll-padding-top: 75px;
// 		margin: auto;
// 		display: flex;
// 		flex-direction: column;

// 		.title {
// 			text-align: center;
// 			color: transparent;
// 			font-family: 'Metal Mania';

// 			letter-spacing: 3px;

// 			font-size: 1.3rem;
// 			background-position: -5px;
// 			h1,
// 			a {
// 				background: -webkit-linear-gradient(gold, gold, red);
// 				background-clip: text;
// 				-webkit-background-clip: text;
// 				-webkit-text-fill-color: transparent;
// 			}
// 			h1 {
// 				font-size: 2rem;
// 			}

// 			display: flex;
// 			margin: 0px 30px;
// 			div {
// 				display: flex;
// 				flex-direction: row-reverse;
// 				align-items: center;
// 				flex-grow: 1;
// 			}
// 		}
// 	}	
// iframe{
// 	margin: 1% auto ;
// 	width: 75vw;
// 	height: 80vh;
// }
// .glimpses{
// 	height: 100vh;
// }

// @media screen and (max-width: 900px) {
// 	iframe{
// 		height: 30vh;
// 		width: 90vw;
// 		margin-top: 5vh;
// 		margin-bottom: 0px;
// 	}
// 	.glimpses{
// 		height: 70vh ;
// 		padding : 0px;
// 	}
// }

.newmeraz{
	width: 80%;
	z-index: 2;
}

.section {
  position: relative;
  width: 100%;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
}

.section h1 {
  text-align: center;
  font-size: 6rem;
  font-family: "Cookie";
  padding: 20px;
  margin: 15px;
  z-index: 1;
  opacity: 0.7;
}



.video-container {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  z-index: 1;
}

.color-overlay {
  position: absolute;
  top: 0;
  left: 0;
  background-color: black;
  width: 100%;
  height: 100vh;
  opacity: 0.7;
}

//Colours







 


// Basic Button Style
.btn {
	position: absolute;
	bottom: 20%;
	z-index: 3;
  box-sizing: border-box;
  appearance: none;
  background-color: transparent;
  border: 2px solid red;
  border-radius: 0.6em;
  color: red;
  cursor: pointer;
  display: flex;
  align-self: center;
  font-size: 1rem;
  font-weight: 400;
  line-height: 1;
  margin: 20px;
  padding: 1.2em 2.8em;
  text-decoration: none;
  text-align: center;
  text-transform: uppercase;
  font-family: 'Montserrat', sans-serif;
  font-weight: 700;

  &:hover,
  &:focus {
    color: #fff;
    outline: 0;
  }
}




.third {
  border-color: #3498db;
  color: #fff;
  box-shadow: 0 0 40px 40px #3498db inset, 0 0 0 0 #3498db;
  transition: all 150ms ease-in-out;
  
  &:hover {
    box-shadow: 0 0 10px 0 #3498db inset, 0 0 10px 4px #3498db;
  }
}

.section1{
  position: relative;
  width: 100%;
  height: 130vh;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden; 
  background:url("assets/bg3.png") center top/auto 100% no-repeat;

  background-size: contain;
  // background-repeat: no-repeat;
}
.section2{
  position: relative;
  top:-80px;
  width: 100%;
  height: 80vh;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden; 
  background-color: white;
  background-size: contain;
  background-repeat: no-repeat;
}
.section3{
  position: relative;
  top: -50px;
  width: 100%;
  height: 130vh;
  display: flex;
  align-items: center;
  justify-content: center;
  background:url("assets/bg3.png") center top/auto 100% no-repeat;
  overflow: visible; 
  background-image: url("assets/bg3.png");
  background-size: contain;
}
@media (max-width: 900px) {
  .video{
    width:420px;
    height:80%;
    left:10%;
    right: 10%;
    top: 10%;
  }
  .video1{
    width:420px;
    height:80%;
    left:10%;
    right: 10%;
    top: 30%;
  }
  .video2{
    width:420px;
    height:80%;
    left:10%;
    right: 10%;
    top: 20%;
  }
    .text{
    top: 10px;
    width: 100%;
    height: 100%;
  }
  .text1{
    top: 10px;
    width: 100%;
    height: 100%;
  }
  .text2{
    top:10px;
    width: 100%;
    height: 100%;
  }
  .section1{
    height: 80vh;
    background-size: cover;
  }
  .section2{
    height: 60vh;
    background-size: cover;

  }
  .section3{
    height:80vh;
    background-size: cover;
  }
	}

</style>
