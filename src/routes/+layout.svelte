<script>
import { AppBar } from '@skeletonlabs/skeleton';
import { LightSwitch } from '@skeletonlabs/skeleton';
import "../app.css";
</script>


<AppBar>
	<!-- <svelte:fragment slot="lead"></svelte:fragment> -->
	Code Switching IO
	<svelte:fragment slot="trail"><LightSwitch /></svelte:fragment>
</AppBar>
<slot></slot>
