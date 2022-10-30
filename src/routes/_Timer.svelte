<script>
	import { onMount } from 'svelte';

	const END_TIME = new Date('Nov 11, 2022 00:00:00').getTime(); // End time of timer
	const TIMER_INTERVAL = 1000;

	let timeLeft = { days: 0, hours: 0, minutes: 0, seconds: 0 },
		complete = false;

	onMount(updateTime);
	let interval = setInterval(updateTime, TIMER_INTERVAL);

	function updateTime() {
		const totalSeconds = END_TIME - Date.now();
		if (totalSeconds <= 0) {
			clearInterval(interval);
			complete = true;
		}
		timeLeft = {
			days: Math.floor(totalSeconds / (1000 * 60 * 60 * 24)),
			hours: Math.floor((totalSeconds % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60)),
			minutes: Math.floor((totalSeconds % (1000 * 60 * 60)) / (1000 * 60)),
			seconds: Math.floor((totalSeconds % (1000 * 60)) / 1000),
		};
	}
</script>

{#if complete}
	<!-- <div class="complete-message">Nov 8-10, 2019</div> -->
	<div class="complete-message">Stay Tuned</div>
{:else}
	<div class="parent">
		<div class="box">
			{timeLeft.days}
			<span>Days</span>
		</div>
		<div class="box">
			{timeLeft.hours}
			<span>Hours</span>
		</div>
		<div class="box">
			{timeLeft.minutes}
			<span>Minutes</span>
		</div>
		<div class="box">
			{timeLeft.seconds}
			<span>Seconds</span>
		</div>
	</div>
{/if}

<style lang="scss">
	.parent {
		display: flex;
		justify-content: space-around;
		margin: 0;
	}

	.complete-message,
	.parent {
		color: var(--primary);
		font-family: 'Metal Mania', cursive;

		letter-spacing: 3px;

		// font-family: nouty;
		// letter-spacing: 3px;

		background-image: url('/assets/gold-texture.jpg');
		background-repeat: repeat-x;
		background-position: 0 0;
		font-size: 1.9rem;
		text-transform: uppercase;
		text-align: center;
		color: transparent;
		-webkit-font-smoothing: antialiased;

		background-clip: text;
		-webkit-background-clip: text;
		-moz-background-clip: text;
		-webkit-text-fill-color: transparent;

		-webkit-animation: BackgroundAnimated 10s linear infinite;
		-moz-animation: BackgroundAnimated 10s linear infinite;
		-ms-animation: BackgroundAnimated 10s linear infinite;
		-o-animation: BackgroundAnimated 10s linear infinite;
		animation: BackgroundAnimated 10s linear infinite;
	}

	.complete-message {
		padding-top: 30px;
	}

	@keyframes BackgroundAnimated {
		from {
			background-position: 0 0;
		}
		to {
			background-position: 0 100%;
		}
	}
	@-webkit-keyframes BackgroundAnimated {
		from {
			background-position: 0 0;
		}
		to {
			background-position: 0 100%;
		}
	}
	@-ms-keyframes BackgroundAnimated {
		from {
			background-position: 0 0;
		}
		to {
			background-position: 0 100%;
		}
	}
	@-moz-keyframes BackgroundAnimated {
		from {
			background-position: 0 0;
		}
		to {
			background-position: 0 100%;
		}
	}

	.box {
		font-size: 1.9rem;
		display: flex;
		flex-direction: column;
		padding: 5px;
	}
	.box > span {
		font-size: 1.1rem;
	}
</style>
