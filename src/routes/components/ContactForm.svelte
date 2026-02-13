<script>
	import Container from './Container.svelte';
	import Section from './Section.svelte';
</script>

<Section class="py-20" id="contact">
	<Container class="flex flex-col gap-12 lg:flex-row lg:gap-20">
		<div class="flex-1 text-white">
			<h2 class="text-[1.4rem] leading-tight font-bold text-[#32a384] sm:text-[1.7rem] lg:text-[2rem]">
				Meet the teams behind<br />Equatys at MWC Barcelona
			</h2>
			<p class="mt-6 text-[1rem] leading-relaxed font-light text-[#1d295d]">
				Register your interest to meet the team behind Equatys and discuss how shared,
				standards-based satellite infrastructure can support your D2D strategy, NTN integration, and
				long-term mobility roadmap.
			</p>
			<p class="mt-6 text-[1rem] leading-relaxed font-bold text-[#1d295d]">
				Complete the form and our team will contact you to arrange a meeting, and provide you with a
				complimentary MWC pass, if needed.
			</p>
		</div>
		<div class="flex flex-1 items-center justify-center">
			<div class="mt-4 flex items-center justify-center">
				<a
					href="https://are01.safelinks.protection.outlook.com/?url=https%3A%2F%2Fviasat.jifflenow.com%2Fexternal-request%2Fmwc2026%2Fmeeting-request%3Ftoken%3D3c82b5ad92f4dd939dc6&data=05%7C02%7Cahmed.dziri%40Space42.ai%7C3ade4b2ea2794dcb751208de6a12c46d%7C59e03edcf2454e59814750ba17496313%7C0%7C0%7C639064826013394754%7CUnknown%7CTWFpbGZsb3d8eyJFbXB0eU1hcGkiOnRydWUsIlYiOiIwLjAuMDAwMCIsIlAiOiJXaW4zMiIsIkFOIjoiTWFpbCIsIldUIjoyfQ%3D%3D%7C0%7C%7C%7C&sdata=xlWNSXDGJcfyEgkGGn6wJWhKk6dh%2Bm8Y1kAaXWPfsG0%3D&reserved=0"
					class="rounded-b-lg px-10 py-3 text-[1rem] font-semibold text-white transition-opacity hover:opacity-90 sm:px-16 sm:py-4 sm:text-[1.3rem]"
					style="background: linear-gradient(to right, #00ae84, #1d295d)"
					target="_blank"
				>
					Book a meeting
				</a>
			</div>
			<!-- <form class="flex flex-col gap-6">
				<div class="flex flex-col gap-1">
					<label for="fullname" class="text-sm text-white/70">Full name</label>
					<input
						type="text"
						id="fullname"
						name="fullname"
						class="border-b border-white/30 bg-transparent py-2 text-white outline-none focus:border-white"
					/>
				</div>
				<div class="flex flex-col gap-1">
					<label for="email" class="text-sm text-white/70">Business email</label>
					<input
						type="email"
						id="email"
						name="email"
						class="border-b border-white/30 bg-transparent py-2 text-white outline-none focus:border-white"
					/>
				</div>
				<div class="flex flex-col gap-1">
					<label for="phone" class="text-sm text-white/70">Phone number</label>
					<input
						type="tel"
						id="phone"
						name="phone"
						class="border-b border-white/30 bg-transparent py-2 text-white outline-none focus:border-white"
					/>
				</div>
				<div class="flex flex-col gap-1">
					<label for="company" class="text-sm text-white/70">Company name</label>
					<input
						type="text"
						id="company"
						name="company"
						class="border-b border-white/30 bg-transparent py-2 text-white outline-none focus:border-white"
					/>
				</div>
				
			</form> -->
		</div>
	</Container>
</Section>
