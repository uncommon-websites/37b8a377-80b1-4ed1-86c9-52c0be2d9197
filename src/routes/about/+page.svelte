<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Innovation",
			description: "Constantly challenging the status quo to create better solutions."
		},
		{
			title: "Integrity",
			description: "Building trust through transparent actions and honest communication."
		},
		{
			title: "Impact",
			description: "Measuring our success by the positive change we create for our clients."
		}
	];
</script>

<SecondaryHero
	title="Decisions made faster"
	subtitle="Because the ocean doesn't wait"
	imageSrc="/generated/image-a-diverse-maritime-team-collaborating-in.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"It started with a simple question from a veteran logistics operator: \"Why are we still planning routes like it's 1999?\" Our team saw global fleets losing millions every year because of slow data, static routing models, and manual decision-making. Vessels were stuck in delays they could have avoided—if only the systems they relied on moved as fast as the ocean itself.",
		"Navys closes that gap. We process fresh satellite imagery, AIS signals, and real-time weather patterns through predictive algorithms to deliver instant routing recommendations. When tested with mid-market operators, our platform reduced inefficiencies by up to 22%. Our edge comes from deep maritime operations experience combined with unmatched geospatial data fluency—so the system thinks like a mariner and moves like a machine.",
		"Navys now powers smarter, faster decisions across a growing network of 50,000 tracked vessels. We're becoming the operating layer for real-time fleet visibility, contract compliance, and zero-downtime optimization. Our mission is simple: transform maritime logistics for a $150B shipping market that's ready for intelligent infrastructure—vessel by vessel, region by region."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- CTA Section -->
<CallToAction
	title="Ready to collaborate?"
	subtitle="Let's create something amazing"
	description="Join the companies already leveraging our expertise to transform their digital presence and achieve their business goals."
/>
