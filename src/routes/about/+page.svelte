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
			title: "Legal excellence",
			description: "Combining elite legal expertise with military-grade engineering to deliver AI that understands complex legal workflows."
		},
		{
			title: "Attorney-client privilege",
			description: "Building security and confidentiality into every system component with single-tenant architecture and end-to-end encryption."
		},
		{
			title: "Measurable impact",
			description: "Delivering 2.7 hours of daily time savings while transforming fragmented legal knowledge into actionable intelligence."
		}
	];
</script>

<SecondaryHero
	title="Legal expertise meets AI precision"
	subtitle="Because fund closings can't wait"
	imageSrc="/generated/image-a-legal-team-is-collaborating-in-a-moder.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"It started with a simple question from a fund formation partner at Kirkland & Ellis: \"Why are we still drafting fund documents like it's 1999?\" Our founding team saw elite law firms losing millions in billable efficiency because of manual legal processes, static research methods, and repetitive drafting. Lawyers were spending 60+ hours per week on work that delayed fund closings—if only the systems they relied on understood complex legal workflows.",
		"Navys closes that gap. We combine specialized legal AI trained on fund formation expertise with live market intelligence to deliver expert legal responses instantly. Our founding team brings together Amr Jomaa's $50bn+ fund formation experience at Kirkland & Ellis and Cleary Gottlieb, Keith Hickman's military-grade engineering from DoD logistics, and Chanel Bishop's dual perspective as both funds lawyer and financial services regulator. This unique combination creates AI that thinks like an elite lawyer and executes like a precision system.",
		"Navys now powers faster, smarter legal decisions for fund formation partners at top-tier law firms. We're becoming the intelligence layer for complex legal workflows, regulatory compliance, and expert document generation. Our mission is simple: transform the $18.5B legal services market by delivering 2.7 hours of daily time savings to funds lawyers—one firm at a time, one fund at a time."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- CTA Section -->
<CallToAction
	title="Ready to transform your fund formation practice?"
	subtitle="Let's revolutionize legal workflows"
	description="Join the elite law firms already leveraging our specialized legal AI to deliver expert fund documents faster while reclaiming strategic thinking time for complex deals."
/>
