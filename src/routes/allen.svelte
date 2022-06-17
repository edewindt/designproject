<main>
	<body>
		<section class="photo-grid">
			<div class="card card-tall">1</div>
			<div class="card card-tall">2</div>
			<div class="card">3</div>
			<div class="card">4</div>
			<div class="card">5</div>
			<div class="card">6</div>
			<div class="card">7</div>
			<div class="card">8</div>
			<div class="card card-wide">9</div>
			<div class="card card-wide">10</div>
			<div class="card">11</div>
			<div class="card">12</div>
		</section>
	</body>
</main>

<style>
	.photo-grid {
		display: grid;
		gap: 1rem;
		grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
		grid-auto-rows: 240px;
	}
	@media screen and (min-width: 600px) {
		.card-tall {
			grid-row: span 2 / auto;
		}
		.card-wide {
			grid-column: span 2 / auto;
		}
	}
</style>
