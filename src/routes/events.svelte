<svelte:head>
	<title>Events | Meraz '22</title>
	<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=DotGothic16&family=Oswald:wght@500&family=Silkscreen&display=swap" rel="stylesheet">
</svelte:head>
<div class="bodyy">
	<!-- <div class="empty">

	</div> -->
	<div class="meraz">
		<img alt="not found" class="merazimg" src="/assets/meraz_white.png">
	</div>
	<div class="mains">
		<h1 class="event">EVENTS</h1>
		<div class="background">
			<a href="/pronite"><img alt="not found" class="img1 imag" src="/assets/pronites.png"></a>
			<a href="/culturals"><img alt="not found" class="img2 imag" src="/assets/cultural.png"></a>
			<a href="/scitech"><img alt="not found" class="img3 imag" src="/assets/scitech.png"></a>
			<a href="/informal"><img alt="not found" class="img4 imag" src="/assets/informal.png"> </a>
		</div>
		
		<div class="background2">
			<a href="/pronite"><img alt="not found" class="img1" src="/assets/pron.png"></a>
			<a href="/culturals"><img alt="not found" class="img2" src="/assets/dancenew.png"></a>
			<a href="/scitech"><img alt="not found" class="img3" src="/assets/sciencetech.png"></a>
			<a href="/informal"><img alt="not found" class="img4" src="/assets/informals.png"> </a>
		</div>
	
	</div>

</div>


<style lang="scss">
	.bodyy{
		background-image: url(/assets/bg_event.png);
		background-repeat: no-repeat;
		background-size: cover;
		background-attachment: fixed;
		padding-bottom: 55%;
		}
	.empty{
		height: 40px;
	}
	.mains{
		position: absolute;
		top:2%;
		left:22%;
		margin-bottom: 30px;
		margin-right: 0px;
	}
	.background{
		position: relative;
		display: flex;
		flex-direction:row;
		width:50vw;
		background-color: transparent;
		padding: 2px;
		padding-bottom: 1px;
		border-radius: 40px;
		left:10%;
	}
	.imag{
		transition: .2s all;

	}
	
	.imag:hover{

			// -webkit-filter: brightness(30%);

		
		// content: 'hey i am a text';
		border: 2px solid rgb(117, 255, 227);
		transform: scale(1.2);

}
	.img1{
		// border-radius: 40px 0 0 40px;
	}
	.img4{
		// border-radius: 0 40px 40px 0 ;
	}
	img{
		padding: 2px;
		width:100%;
	}
	.meraz{
		
		position: fixed;
		z-index: 9;
		left:2%;
		top:7%;
		height:100vh;
		width:200px;
		background-color: #58899A;
	}
	.event{
		font-family: 'Oswald', sans-serif;
		font-size:500%;
		// position: absolute;
		position: relative;	
		left: 20%;	
		width:70%;
		margin-bottom: 5%;
		text-align: center;
		z-index: 25
	}
	.merazimg{
		position: relative;
		// opacity:0.5;
		top:5%;
		width:100px;
		left:20%;
	}
	.background2{
		display:none;
	}
	// .img1{
	// 	position: relative;
	// 	left:0%;
	// }
	// .img2{
	// 	position:relative;
	// 	left:25%;
	// }
	// .img3{
	// 	position:relative;
	// 	left:50%;
	// }
	// .img4{
	// 	position:relative;
	// 	left:75%;
	// }
	.poster{
		object-fit:cover;
		
	}
	@media (max-width: 900px) {
	
		.empty{
			height: 100px;

		}
		.background{
			display:none;
			width: 80vw;

			left: 5%;
		}
		.background2{
			display:block;
			width:90%;
			margin-left: 5%;
			margin-right: 5%;
		}
		.mains{
			left:10%;
			top:10%;
		}
		.meraz{
			position: absolute;
			width:30px;
			top:0;
			left:0;
			height: 100%;
			// z-index: ;
		}
		.merazimg{
			display: none;
		}
		.event{
			// font-size: ;
			// margin-right: -0%;top: ;
			font-size: 300%	;
			left: 15%;
			text-align: center;
		}
		.bodyy{
			padding-bottom: 200%;
		}
	
	}
</style>
