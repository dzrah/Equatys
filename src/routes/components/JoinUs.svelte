<script>
	import Container from './Container.svelte';
	import Section from './Section.svelte';
</script>

<Section bgImage="BG.jpg" class="bg-center">
	<Container class="flex flex-col items-center ">
		<h2
			class=" mt-20 text-center text-[1.4rem] font-bold text-[#00ae84] sm:text-[1.7rem] lg:text-[2.1rem]"
		>
			Join us at MWC for bold ideas, smart panels
			<br /><span>and inspired moments</span>
		</h2>
		<div
			class="mt-5 flex w-full flex-col items-center justify-center text-center text-[0.9rem] font-light text-[#1d295d] sm:text-[1rem] md:w-[70%]"
		>
			<p>
				Visit our booth at MWC Barcelona and join an exclusive fireside conversation featuring
				Space42's Managing Director, Karim Sabbagh, and Viasat's CEO, Mark Dankberg; headline
				speakers of the Equatys Partner Program.
			</p>

			<p class="mt-5">
				Meet the team behind Equatys and continue the discussion over light refreshments and
				beverages.
			</p>
			<p class="mt-5">All registered MWC attendees are welcome to attend these sessions.</p>

			<p class="mt-6 text-[1.2rem] font-bold">Hall 6 | Stand 6A20</p>
		</div>

		<!-- Session 1: text left, image right -->
		<div class="mt-25 w-full text-[#1d295d]">
			<div class="grid w-full grid-cols-1 gap-6 md:grid-cols-2 md:gap-10">
				<div class="order-2 flex flex-col md:order-1">
					<p class="mb-8 text-[1.2rem] font-bold">
						NTN at a Crossroads: Open Interoperability or walled Gardens in Space
					</p>
					<p class="text-[1rem] font-light">Date and time: 2 March, 10:30 CET</p>
					<p class="text-[1rem] font-light">Location: Hall 6</p>
					<p class="font-light">
						Speakers: Jassem Nasser, Chief Business Development Officer, Space42 and Kevin Cohen, VP
						Business Development, Viasat
					</p>
				</div>
				<div class="order-1 md:order-2">
					<img class="h-full w-full object-cover" src="Front_Stage.jpg" alt="" />
				</div>
			</div>

			<div class="mt-5">
				<p>
					Overview: NTN's future depends on the architectural choices being made today across
					standards, policy, and ecosystem collaboration.
				</p>
				<a
					class="mt-2 inline-block font-bold uppercase"
					target="_blank"
					href="https://are01.safelinks.protection.outlook.com/?url=https%3A%2F%2Furldefense.us%2Fv3%2F__https%3A%2Fwww.mwcbarcelona.com%2Fagenda%2Fsessions%2F6064-a-shared-value-roadmap-for-space-enabled-global-mobility__%3B!!C5Asm8uRnZQmlRln!eUdicUrc6S5lbpKldEg7_ugo_TgtBTyilpnJdDiE-fXzQvN1VS1TEDj-r58bojTCtXsk39ENEtrA3e6SCUTWsVw8vUhp%24&data=05%7C02%7Cahmed.dziri%40Space42.ai%7C3ade4b2ea2794dcb751208de6a12c46d%7C59e03edcf2454e59814750ba17496313%7C0%7C0%7C639064826013366649%7CUnknown%7CTWFpbGZsb3d8eyJFbXB0eU1hcGkiOnRydWUsIlYiOiIwLjAuMDAwMCIsIlAiOiJXaW4zMiIsIkFOIjoiTWFpbCIsIldUIjoyfQ%3D%3D%7C0%7C%7C%7C&sdata=eu5p6lAYv4rLLh4tLfeQzjElunBHa7VtbExTKArFkuc%3D&reserved=0"
					>SIGN UP FOR THE SESSION &gt;&gt;</a
				>
			</div>
		</div>

		<!-- Session 2: image left, text right -->
		<div class="mt-25 w-full text-[#1d295d]">
			<div class="grid w-full grid-cols-1 gap-6 md:grid-cols-2 md:gap-10">
				<div>
					<img class="h-full w-full object-cover" src="NTN.jpg" alt="" />
				</div>
				<div class="flex flex-col">
					<p class="mb-8 text-[1.2rem] font-bold">
						Satellite & NTN Summit: The future of NTN & 5G extension
					</p>
					<p class="text-[1rem] font-light">Date and time: 4 March, 10:30 - 11:20 CET</p>
					<p class="text-[1rem] font-light">Location: Hall 6 Summit Stage</p>
				</div>
			</div>

			<div class="mt-5">
				<p>
					Overview: This session demonstrates how satellite and non-terrestrial networks extend 5G
					globally, enabling seamless connectivity across consumer, enterprise, IoT, and critical
					services while unlocking new mobility, resilience, and economic opportunity.
				</p>
				<a
					class="mt-2 inline-block font-bold uppercase"
					target="_blank"
					href="https://www.mwcbarcelona.com/agenda/sessions/6135-satellite-and-ntn-summit"
					>SIGN UP FOR THE SESSION &gt;&gt;</a
				>
			</div>
		</div>

		<!-- Session 3: text left, image right -->
		<div class="mt-25 w-full text-[#1d295d]">
			<div class="grid w-full grid-cols-1 gap-6 md:grid-cols-2 md:gap-10">
				<div class="order-2 flex flex-col md:order-1">
					<p class="mb-8 text-[1.2rem] font-bold">
						Half Day Partner Program Space-enabled mobility: Unlocking a competitive, resilience and
						sovereign future
					</p>
					<p class="text-[1rem] font-light">Date and time: 4 March, 15:00 - 17:30 CET</p>
					<p class="text-[1rem] font-light">Location: Theatre 6, Hall 8</p>
				</div>
				<div class="order-1 md:order-2">
					<img class="h-full w-full object-cover" src="Half_Day.jpg" alt="" />
				</div>
			</div>

			<div class="mt-5">
				<p>
					Overview: As space-enabled mobility becomes critical infrastructure, its ability to
					preserve competition, strengthen sovereignty, and expand resilient global connectivity
					will depend on the architectural, governance, and interoperability choices being made
					across networks and borders today.
				</p>
				<a
					class="mt-2 inline-block font-bold uppercase"
					target="_blank"
					href="https://www.mwcbarcelona.com/agenda/sessions/5993-space-enabled-mobility-unlocking-a-competitive-resilient-and-sovereign-future"
					>SIGN UP FOR THE SESSION &gt;&gt;</a
				>
			</div>
		</div>

		<div class="mb-20"></div>
	</Container>
</Section>
