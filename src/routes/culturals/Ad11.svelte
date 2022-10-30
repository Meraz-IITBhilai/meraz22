<svelte:head>
	<title>Ad11 | Meraz '22</title>
</svelte:head>
<div class="bodyy">
	<div class="main-container">
		<div class="poster-container">
			<img class="poster1" src="/assets/overflow.png" alt="overflow" border="0" />
		</div>
		<div class="text-container">
			<div class="top-text">
				<h1 class="event-title">OVERFLOW</h1>
				<h2 class="club-name">Google Developement Student Club</h2>
			</div>
			<img class="top-design-class" src="/assets/top-design-use.png" />
			<div class="description">
				<p>
					The participants will be given a buggy source code of a program and will be shown how the
					debugged program should work.They are expected to identify the bugs, debug the code and
					the one who does it first wins.
				</p>
			</div>
			<div class="details-container">
				<div class="prize-col">
					<img src="/assets/trophy-icon.png" />
					<h3>Total Prize</h3>

					&#8377;2,500<br />
					&#8377;1,500<br />
					&#8377;1,000<br />
				</div>
				<img class="breaker-design" src="/assets/breaker-design-use.png" />
				<div class="poc-col">
					<h3>Point Of Contact:</h3>

					Aditya Sankhla: +91 8369504378<br />
					dsc@iitbhilai.ac.in<br />
				</div>
			</div>
			<img class="bottom" src="/assets/bottom-design-use.png" />
		</div>
	</div>
</div>

<style lang="scss">
	* {
		margin: 0;
		padding: 0;
	}

	.bodyy {
		/* background-color: black; */
		background-image: url('/assets/background-image.png');
		color: white;
		margin-top: 5vw;
		font-family: 'Expletus Sans', cursive;
	}

	.main-container {
		display: flex;
		margin-left: 6%;
		margin-right: 6%;
		object-fit: contain;
		flex-grow: 1;
		height: 60vw;
	}

	.poster-container {
		flex-basis: 70%;
		/* flex-grow: 1; */
	}
	.poster1 {
		width: 100%;
		height: auto;
		border: 2px solid teal;
		border-radius: 2px;
	}
	.text-container {
		padding: 2% 3%;
		/* flex-grow:3; */
	}

	.event-title {
		font-size: 2vw;
		padding-left: 1vw;
	}

	.club-name {
		font-size: 1.3vw;
		padding-top: 0.5vw;
		font-family: 'Expletus Sans', cursive;
		padding-left: 1vw;
	}

	img {
		max-width: 100%;
	}

	.top-design-class {
		margin-top: 1vw;
	}

	.description {
		padding-left: 0.8vw;
		padding-right: 0.8vw;
		min-height: 10vw;
		font-family: 'Expletus Sans', cursive;
	}

	.description p {
		line-height: 25px;
		margin-top: 2vw;
		/* font-size: 1.1vw; */
	}

	.details-container {
		padding: 3.2vw;
		display: grid;
		grid-template-columns: 45% 10% 45%;
		line-height: 25px;
	}

	.breaker-design {
		height: 10vw;
		width: auto;
	}

	.prize-col {
		text-align: center;
	}

	.prize-col img {
		display: inline;
	}
	.poc-col {
		display: flex;
		justify-content: center;
		align-content: center;
		flex-direction: column;
		text-align: center;
	}
</style>
