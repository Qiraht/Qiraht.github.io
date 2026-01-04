<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();

	const name: String = 'Thariq';
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<title>{name}'s Portfolio</title>
</svelte:head>

<header class="text-gray-600 body-font sticky top-0 bg-gray-200 shadow-md z-10">
	<div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
		<nav class="md:ml-auto md:mr-auto flex flex-wrap items-center text-base justify-center">
			<a class="mr-5 hover:text-gray-900 hover:underline" href="#home">1. home</a>
			<a class="mr-5 hover:text-gray-900 hover:underline" href="#about">2. about</a>
			<a class="mr-5 hover:text-gray-900 hover:underline" href="#projects">3. projects</a>
			<a class="mr-5 hover:text-gray-900 hover:underline" href="#contact">4. contact</a>
		</nav>
	</div>
</header>

{@render children()}
