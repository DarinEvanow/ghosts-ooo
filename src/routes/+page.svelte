<script lang="ts">
	import App from '$lib/App.svelte';
</script>

<div>
	<App />
</div>

<style>
	:global(*) {
		margin: 0;
		padding: 0;
		border: 0;
		outline: 0;
		font-size: 100%;
		vertical-align: baseline;
	}

	div {
		height: 100vh;
		width: 100vw;
	}
</style>
