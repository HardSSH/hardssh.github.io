<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>
<div class="container mx-auto p-4 max-w-2xl min-h-dvh font-serif">
{@render children()}
</div>
