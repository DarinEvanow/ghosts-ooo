<script>
	import { T } from '@threlte/core';
	import Ground from '$lib/Ground.svelte';
</script>

<T.PerspectiveCamera
	makeDefault
	position={[10, 10, 10]}
	on:create={({ ref }) => {
		ref.lookAt(0, 1, 0);
	}}
/>

<T.DirectionalLight position={[3, 10, 7]} />

<Ground />
