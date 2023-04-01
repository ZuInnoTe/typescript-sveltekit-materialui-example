<script lang="ts">
	import { assets } from '$app/paths';
</script>

<svelte:head>
	<!-- SMUI Styles -->
	<link rel="stylesheet" href="{assets}/css/smui.css" />

	<!-- Site Styles -->
	<link rel="stylesheet" href="{assets}/css/site.css" />

	<!-- Site Styles -->
	<link rel="stylesheet" href="{assets}/css/site.css" media="(prefers-color-scheme: light)" />
	<link
		rel="stylesheet"
		href="{assets}/css/site-dark.css"
		media="screen and (prefers-color-scheme: dark)"
	/>
</svelte:head>
<slot />
