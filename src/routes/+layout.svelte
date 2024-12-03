<script lang="ts">
	import { ModeWatcher } from 'mode-watcher';
	import '@fontsource-variable/dm-sans';
	import '../app.css';
	import Sonner from '$lib/components/ui/sonner/sonner.svelte';
	let { children } = $props();
</script>

<ModeWatcher />
<Sonner />

{@render children()}
