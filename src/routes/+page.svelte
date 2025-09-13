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
	title="Securing Europe's critical infrastructure networks"
	subtitle="Trusted by leading European enterprises and defense contractors to build resilient security architecture that meets the most stringent compliance requirements."
	centered={true}
	customers={[
		{
			name: "Klaus Weber",
			position: "CISO, European Defense Systems",
			imageSrc: "/generated/image-a-professional-european-male-cybersecuri.webp"
		},
		{
			name: "Elena Rossi",
			position: "Head of Security, Continental Networks",
			imageSrc: "/generated/image-a-professional-european-female-security-.webp"
		},
		{
			name: "Henrik Johansson",
			position: "Chief Security Officer, Nordic Infrastructure",
			imageSrc: "/generated/image-a-professional-european-male-chief-secur.webp"
		},
		{
			name: "Marie Dubois",
			position: "Director of Cybersecurity, Atlantic Defense",
			imageSrc: "/generated/image-a-professional-european-female-technolog.webp"
		},
		{
			name: "Andreas Mueller",
			position: "Security Director, Central European Alliance",
			imageSrc: "/generated/image-a-professional-european-male-defense-con.webp"
		}
	]}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/siemens.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/schneider-electric.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/engie.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/volkswagen.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	generating
	testimonials={[
		{
			name: "Jane Smith",
			position: "CTO",
			company: "Tech Innovations",
			quote:
				"Their cutting-edge automation boosted our productivity by 35%.\nThe intuitive interface reduced training time and improved team adoption.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "John Doe",
			position: "Director of Operations",
			company: "Global Solutions",
			quote:
				"Their robust security protocols gave us confidence in handling sensitive data.\nThe 24/7 support team resolved issues within hours, not days.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Sarah Johnson",
			position: "Product Manager",
			company: "Future Systems",
			quote:
				"The scalable platform grew seamlessly with our business needs.\nTheir customization options allowed us to tailor solutions perfectly to our workflows.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<Features
	generating
	title="Features"
	subtitle="Some features"
	features={[
		{
			title: "Streamlined Workflows",
			description:
				"Automate repetitive tasks and connect systems to improve productivity with our industry-leading 87% time savings."
		},
		{
			title: "Data Analysis",
			description:
				"Extract meaningful insights from your data with powerful analytical tools backed by proprietary AI algorithms that are 3x more accurate than competitors."
		},
		{
			title: "Secure Collaboration",
			description:
				"Work together seamlessly while maintaining strict data privacy standards with our zero-knowledge architecture and military-grade encryption."
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
