<script>
	import Container from './Container.svelte';
	import Section from './Section.svelte';
</script>

<Section
	class="relative flex h-screen w-full items-center justify-center bg-cover  bg-bottom bg-no-repeat"
	bgImage="Hero.jpg"
>
	<Container class="relative mb-20 flex items-center justify-center lg:mb-40">
		<div
			class="w-full flex-col items-center justify-center text-amber-50"
		>
			<h1 class="font-antarctica text-[2.2rem] font-bold sm:text-[3rem] lg:text-[4rem]">Mobility Everywhere</h1>
			<div class="mt-7 flex-col text-[0.7rem] sm:text-[0.9rem] lg:text-[1.1rem] xl:text-[1.4rem]">
				<div>
					<p class="font-antartica font-light">Equatys, a venture designed to enable global</p>
					<p class="font-antartica font-light">
						Direct-to-Device (D2D) services and Advanced Mobile
					</p>
					<p class="font-antartica font-light">
						Satellite Solutions, invites you to join us at MWC 2026.
					</p>
				</div>
				<div>
					<p class="font-antartica font-light">SPACE-BASED. EARTH-FOCUSED.</p>
				</div>
			</div>
			<img class="mt-12 w-50 sm:w-65 lg:w-90" src="S42_Via.svg" alt="" />
		</div>
	</Container>
</Section>
