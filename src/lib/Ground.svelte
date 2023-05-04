<script lang="ts">
	import { T } from '@threlte/core';
</script>

<T.Mesh position={[0, 0, 0]} rotation={[-Math.PI * 0.5, 0, 0]}>
	<T.PlaneGeometry args={[20, 20]} />
	<T.MeshStandardMaterial color="#288f81" />
</T.Mesh>
