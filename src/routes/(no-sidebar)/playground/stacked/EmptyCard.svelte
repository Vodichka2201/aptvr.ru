<script lang="ts">
	import { Card } from 'flowbite-svelte';
</script>

<Card {...$$restProps}>
	<div
		class="rounded border border-dashed border-gray-200 px-4 py-2 text-gray-400 dark:border-gray-600"
	>
		<h3>Project header</h3>
	</div>
	<div
		class="h-full rounded border border-dashed border-gray-200 px-4 py-2 text-gray-400 dark:border-gray-600"
	>
		<h3>Project body</h3>
	</div>
</Card>
