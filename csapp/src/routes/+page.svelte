
<script>
	import { Divider } from '@brainandbones/skeleton';
	
	import { Tooltip, Button } from 'flowbite-svelte';
	//import { tooltip } from '@brainandbones/skeleton';
</script>

<div>
<Divider borderWidth="border-t-8" borderStyle="border-solid" borderColor="border-primary-400"/>
</div>
<br>


<Button id="hover">Tooltip hover</Button>
<Tooltip triggeredBy="#hover">Hover tooltip content</Tooltip>
<!-- <button use:tooltip={{ content: 'Skeleton' }}>Trigger</button> -->
