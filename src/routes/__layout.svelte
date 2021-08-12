<script>
	import '../app.postcss';
	import Header from '$lib/components/Header.svelte';
	import Footer from '$lib/components/Footer.svelte';
</script>

<div class="bg-gray-200 h-full w-full min-h-screen">
	<div class="w-full max-w-screen-xl mx-auto">
		<Header />
		<main class="px-6">
			<slot />
		</main>
		<Footer />
	</div>
</div>
