<script>
	import { onMount } from 'svelte';
	import Icon, { Code, Briefcase } from 'svelte-hero-icons';
</script>

<section class="flex mt-24">
	<div class="w-2/5">
		<h1 class="text-5xl font-medium">Save yourself 20 hours of development time</h1>
		<h2 class="text-4xl mt-20">The only boilerplate for your next Svelte Kit App</h2>
		<div class="mt-20">
			<a
				href="/getting-started"
				sveltekit:prefetch
				class="btn bg-secondary-600 hover:bg-secondary-700 text-white text-2xl font-normal px-6 py-4"
				>Start Building</a
			>
		</div>
	</div>

	<div class="relative w-3/5">
		<div class=" rounded-full overflow-hidden">
			<img src="/backpack.png" class="aspect-h-10 aspect-w-10" alt="Backpack" />
		</div>
		<span class="bg-white rounded-2xl absolute top-24 flex">
			<div class="rounded-full grid place-items-center">
				<div class="p-4 bg-secondary-600 rounded-full">
					<Icon src={Code} class="h-10 w-10 text-white " />
				</div>
			</div>
			<div class="text-2xl text-gray-800 p-8">Save 20 hours</div>
		</span>

		<span class="bg-white rounded-2xl absolute top-96 -right-48 flex p-8">
			<div class="rounded-full grid place-items-center">
				<div class="p-4 bg-primary-600 rounded-full">
					<Icon src={Briefcase} class="h-10 w-10 text-white " />
				</div>
			</div>
			<div class="text-2xl text-gray-800 p-8">Get onto Business logic faster</div>
		</span>
	</div>
</section>
