<script lang="ts">
	import CTASection from '$lib/components/samples/CTASection.svelte';
	import SomeText from '$lib/components/samples/SomeText.svelte';
</script>

<svelte:head>
	<title>sveltekit-tailwind</title>
</svelte:head>

<div class="flex flex-col gap-8 min-h-[80vh] justify-center items-center text-center">
	<SomeText />
	<CTASection />
</div>
