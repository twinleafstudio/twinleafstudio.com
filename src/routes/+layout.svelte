<script lang="ts">
	import '@skeletonlabs/skeleton/themes/theme-skeleton.css';
	import '@skeletonlabs/skeleton/styles/skeleton.css';
	import '../theme.postcss';
</script>

<main class="flex flex-col items-center justify-center h-screen bg-primary-500 text-surface-500">
	<div class="px-10">
		<slot />
	</div>
</main>
