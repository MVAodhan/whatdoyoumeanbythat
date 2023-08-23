<script lang="ts">
	import { Howl } from 'howler';

	let sound = new Howl({
		src: ['wdymbt.mp3']
	});
</script>

<main>
	<button on:click={() => sound.play()}>What do you mean by that</button>
</main>

<style>
	main {
		display: flex;
		justify-content: center;
		align-items: center;
		width: 100vw;
		height: 100vh;
		background-color: #525252;
	}

	button {
		padding: 10px;
		border-radius: 5px;
		border: none;
	}
</style>
