<script lang="ts">
	import Button, { Label } from '@smui/button';

	let clicked = 0;
</script>

<Button on:click={() => clicked++}>
	<Label>Click me</Label>
</Button>

Clicked button: {clicked}
