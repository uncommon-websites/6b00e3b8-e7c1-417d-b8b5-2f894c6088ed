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
	title="Accelerate real estate value creation with specialized operational expertise"
	subtitle="Kenzu deploys proven operators who combine deal execution experience with property-level expertise to increase NOI by 15-30% within 18 months."
	customers={[
		{
			name: "Jennifer Martinez",
			position: "Managing Director, Brookfield Asset Management",
			imageSrc: "/generated/image-editorial-style-environmental-portrait-o.webp"
		},
		{
			name: "Michael Chen",
			position: "Partner, Blackstone Real Estate",
			imageSrc: "/generated/image-editorial-environmental-portrait-of-a-pr.webp"
		},
		{
			name: "Rebecca Thompson",
			position: "VP Portfolio Management, Carlyle Group",
			imageSrc: "/generated/image-editorial-portrait-of-a-professional-wom.webp"
		},
		{
			name: "David Richardson",
			position: "Senior Partner, Brookfield Capital",
			imageSrc: "/generated/image-editorial-business-portrait-of-a-profess.webp"
		}
	]}
/>
<LogoScroller
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/blackstone.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/brookfield.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/kkr.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/carlyle.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Kenzu partners with mid-market private equity firms to unlock value in real estate portfolios under $500M. We deploy specialized operators who bring both deal execution experience and property-level operational expertise to your portfolio companies, delivering 15-30% NOI increases within 18 months. While traditional consultants offer generic advice, our team executes hands-on improvements that directly impact your bottom line."
/>

<Testimonials
	testimonials={[
		{
			name: "Marcus Wellington",
			position: "Managing Partner",
			company: "Crescent Capital Partners",
			quote:
				"Kenzu compressed our due diligence timeline from 90 days to 45 days on a $180M multifamily acquisition. Their operators identified $2.3M in hidden operational upside that our investment committee hadn't spotted. That accelerated close gave us the competitive edge to win the deal.",
			image: "/generated/image-confident-male-executive-in-a-tailored-s.webp"
		},
		{
			name: "Diana Ramirez",
			position: "Partner, Real Estate Investments",
			company: "Northbridge Equity Group",
			quote:
				"We brought Kenzu into three struggling office properties in our portfolio. Within 14 months, they increased NOI by 22% across all three assets through operational improvements we didn't have the in-house expertise to execute. That translated to $8.4M in additional value at exit.",
			image: "/generated/image-professional-female-executive-in-busines.webp"
		},
		{
			name: "Thomas Bradford",
			position: "Senior Partner",
			company: "Meridian Investment Holdings",
			quote:
				"Before Kenzu, we were missing critical operational risks during acquisition due diligence. Their team caught deferred maintenance issues and tenant lease vulnerabilities that would have cost us $1.7M post-close. They've become our go-to resource for every real estate deal we evaluate.",
			image: "/generated/image-professional-male-partner-in-a-sharp-bus.webp"
		}
	]}
/>

<Features
	title="Specialized operational expertise that drives portfolio value"
	subtitle="Deploy proven operators who combine deal execution experience with property-level capabilities to accelerate returns across your real estate investments."
	features={[
		{
			title: "Accelerated due diligence",
			description:
				"Evaluate acquisition opportunities 40% faster with specialized operators who have closed over $2B in real estate transactions."
		},
		{
			title: "Property-level NOI optimization",
			description:
				"Increase net operating income by 15-30% within 18 months through targeted operational improvements and expense management."
		},
		{
			title: "Embedded operational support",
			description:
				"Access dedicated operators who work alongside your portfolio companies to implement value creation strategies from day one."
		},
		{
			title: "Deal execution expertise",
			description:
				"Leverage operators who understand both the investment thesis and the property-level tactics required to achieve target returns."
		},
		{
			title: "Portfolio-wide consistency",
			description:
				"Deploy standardized best practices across your entire real estate portfolio to ensure repeatable value creation at scale."
		},
		{
			title: "Risk mitigation",
			description:
				"Identify operational risks early in the acquisition process with thorough property-level due diligence from experienced operators."
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Turn insights into NOI, faster"
	subtitle="Ready to accelerate your portfolio?"
	description="Move faster on deals and drive meaningful performance gains across your real estate platform. Our experienced operators are ready to support your team instantly—no ramp-up required."
	imageSrc="/generated/image-a-confident-private-equity-partner-stand.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Schedule a portfolio review",
			variant: "primary"
		},
		{
			href: "/case-studies",
			label: "See case studies",
			variant: "secondary"
		}
	]}
/>
