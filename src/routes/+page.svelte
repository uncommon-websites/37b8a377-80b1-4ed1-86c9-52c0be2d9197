<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";

	// Icons
	import IconNavigation from "~icons/lucide/navigation";
	import IconCloudRain from "~icons/lucide/cloud-rain";
	import IconRadar from "~icons/lucide/radar";
	import IconFuel from "~icons/lucide/fuel";
	import IconAnchor from "~icons/lucide/anchor";
	import IconFileText from "~icons/lucide/file-text";
</script>

<CenteredTextOnlyHero
	title="Optimize your maritime routes with real-time ocean intelligence"
	subtitle="Transform shipping operations with predictive algorithms that process live satellite data to deliver instant route optimization for maximum efficiency and cost savings."
	imageSrc="/generated/image-a-group-of-diverse-people-engaging-in-a-.webp"
/>
<LogoScroller 
	label="Trusted by maritime leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/maersk.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/cosco.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/fedex.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/dhl.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Navys transforms maritime logistics by processing real-time ocean data through predictive algorithms to deliver instant route optimization. We serve operations managers at maritime logistics companies who need to maximize vessel efficiency while reducing costs and transit times. Our platform combines satellite data expertise with deep maritime operations knowledge to optimize routes for over 50,000 tracked vessels across the $150B global shipping market."
/>

<Testimonials
	testimonials={[
		{
			name: "Marina Rodriguez",
			position: "Operations Director",
			company: "Pacific Maritime Lines",
			quote:
				"Navys reduced our fuel costs by 18% in just three months through intelligent route optimization.\nWe're saving over $2.3M annually while improving our on-time delivery rate to 97%.",
			image: "/generated/image-professional-headshot-of-a-confident-mar.webp"
		},
		{
			name: "Captain James Chen",
			position: "Fleet Operations Manager",
			company: "TransOceanic Shipping",
			quote:
				"The predictive weather analytics prevented us from encountering two major storms last quarter, avoiding $850K in potential delays and damages.\nOur crews feel safer and our clients trust us more.",
			image: "/generated/image-professional-headshot-of-an-experienced-.webp"
		},
		{
			name: "Dr. Elena Kowalski",
			position: "VP of Maritime Technology",
			company: "Nordic Logistics Group",
			quote:
				"Tracking 12,000 vessels simultaneously used to require a team of 15 people working around the clock.\nNavys automated 80% of our monitoring processes, reducing our operational overhead by $4.2M yearly.",
			image: "/generated/image-professional-headshot-of-a-female-mariti.webp"
		}
	]}
/>

<Features
	title="Maritime intelligence platform"
	subtitle="Advanced features that transform shipping operations through real-time data processing and predictive algorithms"
	features={[
		{
			title: "Real-time route optimization",
			description: "Process live satellite data and ocean conditions to instantly adjust vessel routes for maximum fuel efficiency and time savings.",
			icon: IconNavigation
		},
		{
			title: "Predictive weather analytics",
			description: "Advanced algorithms forecast weather patterns and sea conditions up to 7 days ahead, enabling proactive route planning that avoids costly delays.",
			icon: IconCloudRain
		},
		{
			title: "Fleet tracking dashboard",
			description: "Monitor up to 50,000 vessels simultaneously with precise location data, estimated arrival times, and performance metrics in one unified interface.",
			icon: IconRadar
		},
		{
			title: "Fuel cost optimization",
			description: "Reduce fuel consumption by up to 15% through intelligent route suggestions that account for currents, winds, and vessel specifications.",
			icon: IconFuel
		},
		{
			title: "Port congestion insights",
			description: "Access real-time port data and waiting times to plan arrivals strategically, minimizing delays and demurrage costs.",
			icon: IconAnchor
		},
		{
			title: "Automated compliance reporting",
			description: "Generate regulatory reports instantly with complete voyage documentation, ensuring maritime law compliance without manual paperwork.",
			icon: IconFileText
		}
	]}
/>
<AboutTeaser />
<CallToAction 
	title="Stop wasting hours chasing port updates"
	subtitle="Pick the fastest route"
	description="You're spending 15+ hours a week on vendor contracts. That ends here. Navys automates maritime route management so your team reclaims time and gains a strategic edge. See delays before they cost you with predictive routing based on live satellite input—no manual tracking needed."
	imageSrc="/generated/image-a-cheerful-and-confident-operations-mana.webp"
	callsToAction={[
		{
			href: "/get-started",
			label: "Book your demo",
			variant: "primary"
		},
		{
			href: "/contact",
			label: "Talk to sales",
			variant: "secondary"
		}
	]}
/>
