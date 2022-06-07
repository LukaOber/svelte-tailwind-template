<script lang="ts">
	export let name: string;
</script>

<main class="max-w-xl p-4 mx-auto text-center">
	<h1 class="text-6xl font-thin leading-normal text-blue-600 uppercase">Hello {name}!</h1>
	<p class="custom-style mt-[3rem]">
		Visit the
		<a href="https://svelte.dev/tutorial" class="text-blue-500 underline">Svelte tutorial</a>
		to learn how to build Svelte apps.
	</p>
</main>