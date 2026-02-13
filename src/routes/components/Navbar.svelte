<script>
	import Container from './Container.svelte';
	import Section from './Section.svelte';

	let isOpen = $state(false);

	function toggleMenu() {
		isOpen = !isOpen;
	}

	function closeMenu() {
		isOpen = false;
	}
</script>

<Section bgClass="bg-transparent" class="absolute top-0 right-0 left-0 z-50">
	<Container>
		<nav
			class="flex h-full w-full flex-1 items-center justify-between py-10 text-[0.9rem] text-white"
		>
			<div class="flex h-full w-auto items-start justify-start">
				<a href="/" class="flex items-center justify-start"
					><img class="w-37" src="/Logo.svg" alt="" /></a
				>
			</div>

			<button
				onclick={toggleMenu}
				class="flex h-10 w-10 flex-col items-center justify-center gap-1.5 lg:hidden"
				aria-label="Menu"
				><span
					class="h-0.5 w-6 bg-white transition-all duration-300 {isOpen
						? 'translate-y-2 rotate-45'
						: ''}"
				></span>
				<span class="h-0.5 w-6 bg-white transition-all duration-300 {isOpen ? 'opacity-0' : ''}"
				></span>
				<span
					class="h-0.5 w-6 bg-white transition-all duration-300 {isOpen
						? '-translate-y-2 -rotate-45'
						: ''}"
				></span></button
			>

			<div
				class="hidden h-full w-auto items-center justify-between gap-10 font-extralight text-white lg:flex"
			>
				<a class="transition-opacity hover:opacity-80" href="https://equatys.com">Home</a>
				<a class="transition-opacity hover:opacity-80" href="#contact">Contact Us</a>
			</div>
		</nav>
	</Container>

	{#if isOpen}
		<div class="flex border-t border-white/10 lg:hidden">
			<Container>
				<div class="flex flex-col gap-4 py-4 font-extralight text-white">
					<a href="/" class="py-2 transition-opacity hover:opacity-80" onclick={closeMenu}>
						Home
					</a>
					<a href="#contact" class="py-2 transition-opacity hover:opacity-80" onclick={closeMenu}>
						Contact Us
					</a>
				</div>
			</Container>
		</div>
	{/if}
</Section>
