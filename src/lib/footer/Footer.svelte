<script lang="ts">
	import BottomAppBar, { Section, AutoAdjust } from '@smui-extra/bottom-app-bar';
	import Fab, { Icon } from '@smui/fab';
	import IconButton from '@smui/icon-button';

	let bottomAppBar: BottomAppBar;
</script>

<BottomAppBar bind:this={bottomAppBar}>
	<Section>
		<IconButton class="material-icons">menu</IconButton>
	</Section>
	<Section fabInset>
		<Fab aria-label="New item">
			<Icon class="material-icons">add</Icon>
		</Fab>
	</Section>
	<Section>
		<IconButton class="material-icons" aria-label="Search">search</IconButton>
		<IconButton class="material-icons" aria-label="Settings">settings</IconButton>
	</Section>
</BottomAppBar>
