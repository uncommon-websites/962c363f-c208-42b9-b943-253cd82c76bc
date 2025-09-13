<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Sovereignty-first",
			description: "We respect Europe's data borders and regulatory frameworks. Everything we build is made to uphold EU autonomy, with full transparency and compliance at the core."
		},
		{
			title: "United by defense",
			description: "We believe Europe is strongest when it secures together. Our platform connects networks across the continent to detect and respond as one."
		},
		{
			title: "Engineered for resilience",
			description: "We design for failure, recovery, and auditability from day one. Security isn't just a feature—it's our foundation."
		}
	];
</script>

<SecondaryHero
	title="Securing Europe from within"
	subtitle="Resilience built into every network"
	imageSrc="/generated/image-a-group-of-european-professionals-in-a-m.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"Across Europe, security leaders are under growing pressure to prove regulatory compliance while managing an overwhelming patchwork of disconnected tools. Meeting NIS2, DORA, and GDPR standards is critical—but most tools weren't built with these frameworks in mind. Add sovereignty concerns and foreign-controlled vendors, and the result is a security model that lacks trust, visibility, and scale.",
		"We've engineered a unified cybersecurity platform that turns fragmented systems into a single, regulation-aligned network. By connecting defense infrastructure across the continent and keeping all data processing within EU borders, we ensure full compliance without compromise. Designed by experts who deeply understand the European regulatory landscape, our platform gives CISOs what they've always needed—security that's reliable, sovereign, and built to scale.",
		"Our mission is to protect 500 million endpoints across the continent and become the foundation of Europe's digital resilience. By capturing the $47 billion European cybersecurity market, we're not just solving today's compliance challenges—we're setting the standard for tomorrow's digital defenses. Because securing Europe starts by making the network itself resilient, sovereign, and truly unified."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Our team"
	subtitle="Your partners in innovation"
	stakeholders={[
		{
			name: "Alex Morgan",
			position: "Founder & CEO",
			bio: "Started the company with a vision to transform the industry through innovative solutions.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Jamie Chen",
			position: "Chief Design Officer",
			bio: "Award-winning designer with a passion for creating intuitive and beautiful experiences.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Taylor Wright",
			position: "Head of Engineering",
			bio: "Technology enthusiast focused on building scalable systems that make a difference.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<StakeholderGrid
	stakeholderType="investor"
	title="Backed by the best"
	subtitle="Point Nine, TSIC and others"
	stakeholders={[
		{
			name: "Point Nine Capital",
			image: "https://cdn.brandfetch.io/pointnine.com/w/400/h/400/logo?c=1id_elLz2Bd5Ej-dWo7"
		},
		{
			name: "TSIC Ventures",
			image: "https://cdn.brandfetch.io/tiny.vc/w/400/h/400/logo?c=1a2b3c4d5e"
		},
		{
			name: "Sequoia Capital",
			image: "https://cdn.brandfetch.io/sequoiacap.com/w/400/h/400/logo"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="European compliance is closing in"
	subtitle="Get ahead now"
	description="Prove your EU compliance with a unified security platform built for continental scale. Our infrastructure gives you real-time visibility, full data sovereignty, and clear audit trails across every endpoint—so you're not stitching together tools when the clock runs out."
	imageSrc="/generated/image-a-professional-european-business-person-.webp"
/>
