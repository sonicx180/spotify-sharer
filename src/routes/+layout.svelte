<script lang="ts">
	let { children } = $props();
	import '../app.css'
	import Navbar from '../components/Navbar.svelte'
	import Footer from '../components/Footer.svelte'
</script>


<svelte:head>
	<link rel = "icon" type = "image/png" href = "../spotify-logo.png" />
</svelte:head>

<Navbar />
{@render children?.()}
<Footer />
