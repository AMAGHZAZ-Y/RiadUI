<script>
	import Button from "$lib/components/Button/Button.svelte";
	import TextInput from "$lib/components/TextInput/TextInput.svelte";
</script>

<div class="container">
	<div class="item">
		<Button />
	</div>
	<div class="item">
		<TextInput />
	</div>
</div>

<style scoped lang="sass">
	.container
		display: grid
		gap: 1rem
		justify-content: center
		align-items: center
		padding: 1rem
	.item
		padding: 1rem
</style>
