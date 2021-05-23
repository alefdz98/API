<script>
	import Router from 'svelte-spa-router';
	import Landing from './Landing.svelte';
	import WineTable from './wineAPI/WineTable.svelte';
	import WineEdit from './wineAPI/WineTableEdit.svelte';
	import NotFound from './NotFound.svelte';
	import Info from './Info.svelte';
	import WineGraph from './wineAPI/WineGraph.svelte';
	


	const routes = {
		"/": Landing,
		
		"/wine-production-stats": WineTable,
		"/wine-production-stats/:country/:year": WineEdit,
		"/info": Info,
		"/wine-graph": WineGraph,
		"*": NotFound
	};
</script>

<main>
	<Router {routes} />
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>