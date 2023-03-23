<script>
import "aframe"
// import "aframe-svelte"
// aframe stuff doesn't like getting imported twice, delete above to play around in repl
	
import box from "./lib/Box.svelte"
</script>

<a-scene>
<!-- 	<a-entity svelte={{component: Example, props: { color: "gold" }}} /> -->
	
	<a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
	<a-sky color="#AAAAFF"></a-sky>
	<box color="red"/>
</a-scene>