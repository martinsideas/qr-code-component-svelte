<script>
	import QrCode from './components/QrCode.svelte'

	let styles = {
		App: `
		bg-blue-100
		h-screen
		flex justify-center items-center
		`
	}
</script>

<div class={styles.App}>
	<QrCode/>
</div>