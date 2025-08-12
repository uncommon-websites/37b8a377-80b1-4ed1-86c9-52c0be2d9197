<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CustomerCardHero from "$lib/components/layout/hero-sections/CustomerCardHero.svelte";

	// Icons
	import IconBrain from "~icons/lucide/brain";
	import IconFileSearch from "~icons/lucide/file-search";
	import IconShield from "~icons/lucide/shield";
	import IconClock from "~icons/lucide/clock";
	import IconTrendingUp from "~icons/lucide/trending-up";
	import IconDatabase from "~icons/lucide/database";
</script>

<CustomerCardHero
	title="Save 2.7 hours daily with specialized legal AI"
	subtitle="Transform fund formation workflows with AI that combines elite legal expertise with live market intelligence, delivering expert fund documents faster than ever."
	customers={[
		{
			name: "Sarah Chen",
			position: "Fund Formation Partner",
			imageSrc: "/generated/image-a-professional-fund-formation-lawyer-sta.webp"
		},
		{
			name: "Michael Rodriguez",
			position: "Senior Associate",
			imageSrc: "/generated/image-a-senior-legal-associate-is-captured-in-.webp"
		},
		{
			name: "Emily Thompson",
			position: "Fund Formation Partner",
			imageSrc: "/generated/image-a-fund-formation-partner-at-an-elite-law.webp"
		},
		{
			name: "David Kim",
			position: "Legal Professional",
			imageSrc: "/generated/image-a-legal-professional-reviews-fund-docume.webp"
		}
	]}
/>
<LogoScroller 
	label="Trusted by elite law firms"
	logoUrls={[
		'https://cdn.brandfetch.io/kirkland.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/skadden.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/lw.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/weil.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Navys transforms fund formation workflows by combining specialized legal AI with live market intelligence to deliver expert fund documents faster than ever. We serve fund formation partners and senior associates at top-tier law firms who need to deliver complex fund documents for demanding GP clients while reducing the 60+ hours per week spent on repetitive drafting and research. Our platform captures the $18.5B legal services market by combining Kirkland & Ellis funds expertise with military-grade engineering execution."
/>

<Testimonials
	testimonials={[
		{
			name: "Sarah Chen",
			position: "Fund Formation Partner",
			company: "Kirkland & Ellis",
			quote:
				"Navys saves me 2.7 hours daily on fund formation documents. What used to take 60+ hours per week now flows seamlessly.\nI can handle more complex deals while delivering faster closings for our GP clients.",
			image: "/generated/image-a-professional-fund-formation-lawyer-sta.webp"
		},
		{
			name: "Michael Rodriguez",
			position: "Senior Associate",
			company: "Cleary Gottlieb",
			quote:
				"The live market intelligence feature helped us identify regulatory changes that would have delayed our $2B fund closing by months.\nNavys transforms fragmented legal knowledge into actionable insights.",
			image: "/generated/image-a-senior-legal-associate-is-captured-in-.webp"
		},
		{
			name: "Emily Thompson",
			position: "Fund Formation Partner",
			company: "Macfarlanes",
			quote:
				"Managing multi-jurisdictional fund compliance used to consume entire weekends. Navys automated 80% of our regulatory reporting.\nOur team reclaimed strategic thinking time while maintaining perfect compliance records.",
			image: "/generated/image-a-fund-formation-partner-at-an-elite-law.webp"
		}
	]}
/>

<Features
	title="Legal AI intelligence platform"
	subtitle="Advanced features that transform fund formation workflows through specialized legal AI and live market intelligence"
	features={[
		{
			title: "Specialized legal AI",
			description: "Custom legal language model trained on fund formation expertise that synthesizes internal and external inputs to generate expert responses and document language.",
			icon: IconBrain
		},
		{
			title: "Live market intelligence",
			description: "Continuously scans and synthesizes real-time regulatory updates and market benchmarks to provide comparative analysis of industry-standard deal terms.",
			icon: IconTrendingUp
		},
		{
			title: "Document drafting automation",
			description: "Generate expert fund documents faster with AI that understands complex legal workflows and adapts to client-specific fund terms and negotiated positions.",
			icon: IconFileSearch
		},
		{
			title: "Time savings optimization",
			description: "Save 2.7 hours daily on repetitive drafting and research tasks, transforming fragmented institutional knowledge into coherent, queryable assets.",
			icon: IconClock
		},
		{
			title: "Regulatory compliance tracking",
			description: "Stay aligned with latest laws and regulatory requirements through automated compliance monitoring that prevents costly delays in fund closings.",
			icon: IconShield
		},
		{
			title: "Secure data integration",
			description: "Single-tenant architecture with end-to-end encryption and attorney-client privilege protection, integrating seamlessly with iManage and SharePoint.",
			icon: IconDatabase
		}
	]}
/>
<AboutTeaser />
<CallToAction 
	title="Stop wasting 60+ hours on repetitive legal drafting"
	subtitle="Reclaim your strategic thinking time"
	description="You're spending 60+ hours a week on repetitive fund formation drafting and research. That ends here. Navys combines specialized legal AI with live market intelligence so your team delivers expert fund documents faster while handling more complex deals. Transform fragmented legal knowledge into actionable insights—no manual research needed."
	imageSrc="/generated/image-a-confident-lawyer-is-depicted-in-a-prof.webp"
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
