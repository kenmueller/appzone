<script lang="ts">
	import ORIGIN from '../lib/origin'
</script>

<svelte:head>
	<title>App Zone</title>
</svelte:head>

<main>
	<h1>App Zone</h1>
	<a
		href="itms-services://?action=download-manifest&url={ORIGIN}/manifest.plist"
	>
		Download
	</a>
</main>

<style lang="scss">
	main {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		height: 100%;
		padding: 30px;
		text-align: center;
	}

	a {
		margin-top: 12px;
		padding: 8px 12px;
		text-decoration: none;
		font-weight: 700;
		color: white;
		background: #007aff;
		border-radius: 8px;
	}
</style>
