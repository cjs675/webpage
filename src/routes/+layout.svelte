<script lang="ts">
	import '../app.css';
    import { ModeWatcher } from "mode-watcher"; 
    import ThemeToggle from '$lib/components/ThemeToggle.svelte';
	let { children } = $props();
</script>

<ModeWatcher /> 

<header style="display: flex; justify-content: flex-end; padding: 1rem;">
    <ThemeToggle />
</header>


{@render children()}
