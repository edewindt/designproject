<main>
	<body>
		<h1>I AM GRID3</h1>
		<section class="grid">
			<div class="card card-1">1</div>
			<div class="card card-2">2</div>
			<div class="card card-3">3</div>
			<div class="card card-4">4</div>
			<div class="card card-5">5</div>
			<div class="card card-6">6</div>
			<div class="card card-7">7</div>
			<div class="card card-8">8</div>
			<div class="card card-9">9</div>
			<div class="card card-10">10</div>
			<div class="card card-11">11</div>
			<div class="card card-12">12</div>
		</section>
	</body>
</main>

<style>
	.grid {
		margin: 100px auto;
		padding: 10px;
		display: grid;
		grid-template-columns: repeat(4, 3fr);
		grid-template-rows: repeat(3, 1fr);
	}
	h1 {
		display: flex;
		justify-content: center;
	}
</style>
