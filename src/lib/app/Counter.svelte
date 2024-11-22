<script lang="ts">
	import Button, { Label } from '@smui/button';

	let clicked = 0;
</script>

<Button onclick={() => clicked++}>
	<Label>Click me</Label>
</Button>

Clicked button: {clicked}
