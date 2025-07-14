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

<nav>
    <a href="/">home</a>
    <a href="/about">about</a> 
    <a href="/blog">blog</a>
    <a href="/info_dump">resources</a>
</nav>


{@render children()}
