<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CustomerCardHero from "$lib/components/layout/hero-sections/CustomerCardHero.svelte";
	
	// Icons for Features
	import IconShield from "~icons/lucide/shield";
	import IconFileCheck from "~icons/lucide/file-check";
	import IconMapPin from "~icons/lucide/map-pin";
	import IconLayers from "~icons/lucide/layers";
	import IconRadar from "~icons/lucide/radar";
	import IconLock from "~icons/lucide/lock";
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
	title="Europe's cybersecurity backbone"
	text="We secure Europe at scale by building interconnected defense infrastructure that meets the continent's most demanding cybersecurity requirements—without compromising data sovereignty or speed. Built specifically for CISOs at European critical infrastructure providers who need to meet NIS2 and GDPR compliance quickly, while ensuring all data processing stays within EU borders."
/>

<Testimonials
	testimonials={[
		{
			name: "Björn Lindqvist",
			position: "Chief Information Security Officer",
			company: "Nordic Critical Infrastructure",
			quote:
				"Compliance audit preparation time reduced from 8 weeks to 2 weeks with their automated EU regulation mapping.\nWe achieved GDPR and NIS2 compliance 60% faster while reducing legal review costs by €200K annually.",
			image: "/generated/image-a-professional-european-male-ciso-in-a-m.webp"
		},
		{
			name: "Isabella Fernández",
			position: "Director of Cybersecurity",
			company: "Iberian Defense Systems",
			quote:
				"Threat detection improved by 85% while false positives dropped 70%, saving our SOC team 25 hours per week.\nCritical incident response time decreased from 4 hours to 35 minutes, preventing an estimated €2.3M in potential damages.",
			image: "/generated/image-a-confident-european-female-security-dir.webp"
		},
		{
			name: "Pieter van der Berg",
			position: "Head of Security Operations",
			company: "Dutch Maritime Security Alliance",
			quote:
				"Cross-border threat intelligence sharing reduced security gaps by 90% across our European network.\nInteroperability with existing NATO systems saved €1.8M in infrastructure replacement costs while maintaining full data sovereignty.",
			image: "/generated/image-a-professional-dutch-male-cybersecurity-.webp"
		}
	]}
/>

<Features
	title="Continental-scale security architecture"
	subtitle="Built specifically for European defense contractors and critical infrastructure providers who demand both sovereignty and resilience."
	features={[
		{
			title: "Continental defense network",
			description: "Deploy interconnected security infrastructure across all European networks with unified command and control capabilities that scale from national to continental operations.",
			icon: IconShield
		},
		{
			title: "EU regulatory compliance suite",
			description: "Automatically demonstrate adherence to NIS2, GDPR, and Cyber Resilience Act requirements through built-in compliance frameworks that eliminate manual audit preparation.",
			icon: IconFileCheck
		},
		{
			title: "Data sovereignty guarantee",
			description: "Every byte of data processing remains within EU borders with legally binding sovereignty assurance that gives CISOs confidence in regulatory compliance.",
			icon: IconMapPin
		},
		{
			title: "Unified security operations",
			description: "Replace fragmented security tools with a single integrated platform that provides complete visibility and control across your entire European infrastructure.",
			icon: IconLayers
		},
		{
			title: "Real-time threat intelligence",
			description: "Access continental threat intelligence feeds specifically designed for European attack patterns with automated response capabilities that stop threats in seconds.",
			icon: IconRadar
		},
		{
			title: "Zero-trust architecture",
			description: "Implement military-grade zero-trust security with granular access controls and continuous verification that meets the highest European defense standards.",
			icon: IconLock
		}
	]}
/>

<AboutTeaser />
<CallToAction 
	title="Secure Europe's critical infrastructure"
	subtitle="Prove compliance at continental scale"
	description="Built for European CISOs navigating fragmented security tools and urgent compliance deadlines. Our platform delivers unified protection with guaranteed EU data sovereignty—no patchwork solutions, no regulatory gaps, just defensible security infrastructure that stands up to scrutiny."
	imageSrc="/generated/image-a-professional-and-confident-european-ch.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Book compliance strategy call",
			variant: "primary"
		},
		{
			href: "/demo",
			label: "Request security assessment",
			variant: "secondary"
		}
	]}
/>