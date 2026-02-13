<script>
	import Container from './Container.svelte';
	import Section from './Section.svelte';
</script>

<Section bgClass="bg-transparent" class="py-10" style="background: linear-gradient(to right, #00ae84, #1d295d)">
	<Container class="flex flex-col gap-8 md:flex-row md:items-center md:justify-between">
		<div>
			<img class="w-37" src="/Logo.svg" alt="Equatys" />
		</div>
		<div class="flex flex-col gap-8 text-sm text-white md:flex-row md:gap-16">
			<div>
				<p class="font-bold">Investor Relations Enquiries</p>
				<p class="mt-1 font-light">For investor-related queries, please</p>
				<p class="font-light">reach out to us via email</p>
				<p class="mt-1 font-light">E: investor.relations@equatys.com</p>
			</div>
			<div>
				<p class="font-bold">Media Relations Enquiries</p>
				<p class="mt-1 font-light">For media inquiries, please reach</p>
				<p class="font-light">out to us via email</p>
				<p class="mt-1 font-light">E: media.relations@equatys.com</p>
			</div>
		</div>
	</Container>
</Section>
