<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>
<p>hej</p>

<hr />

<div class="m-auto p-2">
	<input type="date" />
</div>

<div class="mt-4 mb-4 flex flex-wrap">
	<button class="btn btn-blue btn-blue-select">Planta</button>
	<button class="btn btn-blue">Vattna</button>
	<button class="btn btn-blue">Rensa Ögräs</button>
	<button class="btn btn-blue">Skörda</button>
	<button class="btn btn-blue">Kratta</button>
	<button class="btn btn-blue">Beskära</button>
</div>

<div class="mt-8 mb-8 flex flex-wrap">
	<button class="btn btn-green">Gröna ärtor</button>
	<button class="btn btn-green">Gul lök</button>
	<button class="btn btn-green">Grönkål</button>
	<button class="btn btn-green">Vitlök</button>
</div>

<div class="m-auto p-2">
	<input type="text" value="input" />
</div>

<div class="flex flex-wrap items-start text-center">
	<button class="btn btn-green">Lägg till</button>
</div>

<!-- works but has warnings thrown by error lens -->
<style>
	@reference "./layout.css";

	.btn {
		@apply m-auto mb-2 rounded-lg p-2 px-2 py-2 font-semibold text-nowrap shadow-md;
	}

	.btn-blue {
		@apply bg-blue-100 text-blue-900 hover:bg-blue-500 hover:text-white;
	}

	.btn-blue-select {
		@apply bg-blue-500 text-white;
	}

	.btn-green {
		@apply bg-green-600 text-white;
	}

	/* .btn-green-select {
		@apply bg-green-800 text-white;
	} */
</style>
