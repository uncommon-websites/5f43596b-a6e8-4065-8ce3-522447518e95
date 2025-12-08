<script lang="ts">
	import Navbar from "$lib/components/Navbar.svelte";
	import Hero from "$lib/components/Hero.svelte";
	import Logos from "$lib/components/Logos.svelte";
	import ValueProp from "$lib/components/ValueProp.svelte";
	import Solutions from "$lib/components/Solutions.svelte";
	import Integrations from "$lib/components/Integrations.svelte";
	import Testimonial from "$lib/components/Testimonial.svelte";
	import Security from "$lib/components/Security.svelte";
	import Stats from "$lib/components/Stats.svelte";
	import Footer from "$lib/components/Footer.svelte";
</script>

<main class="min-h-screen bg-[#F9F9F9]">
	<Navbar />
	<Hero />
	<Logos />
	<ValueProp />
	<Solutions />
	<Integrations />
	<Testimonial />
	<Security />
	<Stats />
	<Footer />
</main>

