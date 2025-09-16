<script lang="ts">
	import Music from '../components/Music.svelte';
</script>

<main class="main-page">
    <h1> Spotify Sharer</h1>
	<h2>See what people are listening to at the moment.</h2>

	<div class="music-wrapper">
		<Music />
		<Music />
		<Music />
	</div>
</main>

<style>
    .main-page {
        text-align:center;
    }
	.music-wrapper {
		display:flex;
		justify-content: space-between;
		margin:10px;
	}

</style>