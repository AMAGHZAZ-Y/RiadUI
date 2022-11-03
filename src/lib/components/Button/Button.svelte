<script lang="ts">
	import "$lib/style.sass";
	export let Placeholder: string = "Button";
	export let Class: string | null = null;
	export let Id: string | null = null;
</script>

<button class={Class} id={Id}>
	{Placeholder}
</button>

<style scoped lang="sass">
	button
		background-color: white
		color: black
		opacity: .5
		width: fit-content
		height: fit-content
		padding: 0.3rem
		padding-inline: 0.5rem
		border-radius: 0.2rem
		outline: none
		border: none
		transition-duration: 0.2s
		
	button:hover
		opacity: 0.8
	button:focus
		opacity: 0.3
</style>
