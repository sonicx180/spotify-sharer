<script>

let { img_src = '../music_note.png'} = $props();
</script>

<div class = "music-box">
    <img src = {img_src} alt = "A music note" />
    <h3> Name of Music</h3> by <h4> Music Artist</h4>
    <h3> User's Name</h3>
</div>

<style>
 .music-box {
    background-color: var(--bg-lighter);
    padding:10px;
    border-radius:5px;
 }
</style>