<script>
	import Fa from 'svelte-fa/src/fa.svelte';
	import { faPhoneAlt, faEnvelope, faMapMarkedAlt } from '@fortawesome/free-solid-svg-icons';
</script>

<svelte:head>
	<title>Contact | Meraz '22</title>
</svelte:head>
<div class="styler"></div>
<div class="parent" style="background:rgb(66, 66, 66,40%);	border-radius: 12px;">
	<iframe
		title="IIT Bhilai Map"
		id="map-iframe"
		src="https://maps.google.com/maps?width=700&amp;height=440&amp;hl=en&amp;q=IIT%20Bhilai+(Meraz)&amp;ie=UTF8&amp;t=&amp;z=12&amp;iwloc=B&amp;output=embed"
		frameborder="0"
		scrolling="no"
		marginheight="0"
		marginwidth="0"
	/>
	<br />
	<div class="contact-info">
		<h2>
			<Fa icon={faPhoneAlt} />
			<span>Phone</span>
		</h2>
		<ul>
			<!-- <li>Gourav Borkar (Sponsorship Head) ‐ <a href="tel:+918999739404">8999739404</a></li> -->
			<li>Chinmay Ratnaparkhe (CoSA Events Head)‐ <a href="tel:+918290978374">8291978374</a></li>
			<li>Yash Teckchandani (CoSA President) ‐ <a href="tel:+917049500872">7049500872</a></li>
			<li>Rajagopalan R (CoSA Treasurer) ‐ <a href="tel:+918667083459">8667083459</a></li>
			<!-- <li>Aryavrata Singh (Informals Incharge)- <a href="tel:+919725123743">9725123743</a></li> -->
		</ul>
		<br />

		<h2>
			<Fa icon={faEnvelope} />
			<span>E-mail</span>
		</h2>
		<ul>
			<!-- <li>
					<a href="mailto:meraz@iitbhilai.ac.in">meraz@iitbhilai.ac.in </a>
				</li> -->
		<li>
			<a href="mailto:eventshead_cosa@iitbhilai.ac.in">eventshead_cosa@iitbhilai.ac.in </a>
		</li>
		<li>
			<a href="mailto:President_CoSA@iitbhilai.ac.in">President_CoSA@iitbhilai.ac.in </a>
		</li>
		<!-- <li>
			<a href="mailto:management_cosa@iitbhilai.ac.in">
				management_cosa@iitbhilai.ac.in
			</a>
		</li> -->
	</ul>
		<br />

		<h2>
			<Fa icon={faMapMarkedAlt} />
			<span>Address</span>
		</h2>
		<span class="campusAddress">
			Old Dhamtari Rd<br />
			Datrenga, Raipur<br />
			Chhattisgarh, 492015
		</span>
	</div>
</div>

<style lang="scss">
	.styler{
		height: 50px;

	}
	.parent {
		scroll-snap-align: start;
		scroll-margin-top: 75px;
		margin-top: 75px;
		display: flex;

		object-fit: cover;
		border-radius: 12px;
		margin-left: 10px;
		margin-right: 10px;
		border-width: 3px;
		border-style: solid;
		border-image: linear-gradient(135deg, #ff2600, yellow, yellow, #ff2600) 1 round;
	}
	h2 {
		font-weight: normal;
		font-family: 'Metal Mania', cursive;
		color: gold;
		span {
			color: transparent;
			background: -webkit-linear-gradient(gold, gold, red);
			background-clip: text;
			-webkit-background-clip: text;
			-webkit-text-fill-color: transparent;
		}
	}

	iframe {
		width: 100%;
		margin: 12px;
		height: 460px;
	}
	@media (min-width: 800px) {
		.parent {
			margin: 75px;
		}
	}
	@media (max-width: 800px) {
		.parent {
			flex-direction: column;
		}
		iframe {
			width: 90%;
			margin: 5%;
		}
	}

	.contact-info {
		padding: 15px;
		scroll-snap-align: start;
		scroll-margin-top: 75px;
	}

	ul {
		list-style: none;
		padding: 0;
	}
</style>
