<script lang="ts">
	let { children } = $props();
	import Navbar from '../components/Navbar.svelte'
</script>


<svelte:head>
	<link rel = "icon" type = "image/png" href = "../image.png" />
</svelte:head>

<Navbar />
{@render children?.()}
