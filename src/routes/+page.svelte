<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CustomerCardHero from "$lib/components/layout/hero-sections/CustomerCardHero.svelte";
</script>

<CustomerCardHero
	centered={true}
	title="Transform startup ideas into fundable businesses"
	subtitle="Complete product squads that bridge the gap from concept to funding-ready MVP with strategic validation and full-stack expertise."
	customers={[
		{
			name: "Sarah Chen",
			position: "VP of Product",
			imageSrc: "/generated/image-a-professional-woman-executive-standing-.webp"
		},
		{
			name: "Marcus Thompson",
			position: "Director of Engineering",
			imageSrc: "/generated/image-a-professional-man-director-in-a-contemp.webp"
		},
		{
			name: "Elena Rodriguez",
			position: "Head of Product",
			imageSrc: "/generated/image-a-professional-woman-product-leader-at-h.webp"
		},
		{
			name: "David Park",
			position: "VP of Engineering",
			imageSrc: "/generated/image-a-professional-man-vp-in-a-vibrant-start.webp"
		},
		{
			name: "Amara Okafor",
			position: "Chief Product Officer",
			imageSrc: "/generated/image-a-professional-woman-tech-executive-in-a.webp"
		}
	]}
/>
<LogoScroller
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/stripe.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/notion.so/w/400/h/400/logo',
		'https://cdn.brandfetch.io/figma.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/slack.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Why Headway exists"
	text="Product leaders at Series B-D startups face an impossible choice: ship revenue-critical features before their next funding round, or protect existing roadmaps from disruption. Headway eliminates this tradeoff by embedding complete product squads that combine venture building methodology with full-stack expertise, ensuring your most important features launch on time without derailing your team."
/>

<Testimonials
	testimonials={[
		{
			name: "Michelle Zhang",
			position: "VP of Product",
			company: "Velocity Labs",
			quote:
				"Headway delivered our Series B MVP in 12 weeks instead of 6 months, saving us $400K in opportunity cost. Their squad integrated seamlessly with our team and shipped revenue-critical features that secured our $25M funding round.",
			image: "/generated/image-a-confident-professional-asian-woman-in-.webp"
		},
		{
			name: "Jamal Williams",
			position: "Director of Engineering",
			company: "Nexus Dynamics",
			quote:
				"We avoided hiring 4 senior engineers while launching our enterprise product on time. Headway's full-stack expertise eliminated technical debt that would have cost us $300K to fix later, and their validation testing saved us from building the wrong features.",
			image: "/generated/image-a-confident-professional-black-man-in-hi.webp"
		},
		{
			name: "Sofia Ramirez",
			position: "Head of Product",
			company: "Quantum Growth",
			quote:
				"The venture building methodology de-risked our product launch completely. We validated our market fit with real users in 4 weeks, pivoted based on data, and shipped features that drove 180% user engagement. Headway's approach saved us from a costly product failure.",
			image: "/generated/image-a-confident-professional-latina-woman-in.webp"
		}
	]}
/>

<Features
	title="Built for funding outcomes, not deliverable completion"
	subtitle="We bridge the gap between ambitious product vision and fundable reality with complete squads that execute without derailing your existing roadmap."
	features={[
		{
			title: "Funding-aligned success metrics",
			description:
				"We tie our success to your funding outcomes, not just shipping features. Our venture building methodology ensures every sprint moves you closer to your next round with validation metrics that matter to investors."
		},
		{
			title: "Senior engineering capacity on demand",
			description:
				"Deploy battle-tested product squads with CTO-level expertise who integrate seamlessly into your workflow. Ship revenue-critical features without hiring, onboarding delays, or burning out your existing team."
		},
		{
			title: "Strategic validation before scale",
			description:
				"Combine rapid MVP development with rigorous market validation testing. We de-risk your product roadmap by proving features work before you commit engineering resources to full-scale implementation."
		},
		{
			title: "Parallel execution tracks",
			description:
				"Your core team stays focused on existing roadmaps while our squad tackles new initiatives in parallel. Zero disruption to current velocity, maximum acceleration on strategic bets."
		},
		{
			title: "VC network credibility",
			description:
				"Leverage our portfolio company relationships and investor introductions to strengthen your funding narrative. We've helped startups raise $715M by building products that tell compelling growth stories."
		},
		{
			title: "Full-stack product squads",
			description:
				"Get complete teams, not fragmented contractors. Our squads include strategy, design, engineering, and QA working as a unified force to ship production-ready features that scale."
		}
	]}
/>
<AboutTeaser />
<CallToAction 
	title="Ready to move fast and ship what matters?"
	subtitle="Don't wait for hiring cycles or internal bandwidth"
	description="Bring in a team that thinks like a cofounder and builds like an operator. We align to outcomes, not task lists—so you can hit product milestones, revenue goals, and the next raise with confidence."
	imageSrc="/generated/image-a-confident-professional-product-leader-.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Talk to Headway",
			variant: "primary"
		},
		{
			href: "/about",
			label: "Learn our approach",
			variant: "secondary"
		}
	]}
/>
