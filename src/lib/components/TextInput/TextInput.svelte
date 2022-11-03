<script lang="ts">
	export let Placeholder: string | null = "Text Input";
</script>

<input type="text" placeholder={Placeholder} />

<style lang="sass" scoped>
	input
		color: black
		background-color: white
		opacity: 0.5
		outline: none
		border: none
		padding: 0.3rem
		border-radius: 0.2rem
		transition-duration: 0.3s

	input:hover
		opacity: 0.8
	input:focus
		opacity: 0.7
		transition-duration: 0s
</style>
