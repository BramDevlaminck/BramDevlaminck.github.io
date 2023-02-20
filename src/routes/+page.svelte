<script>
	import Experience from './Experience.svelte';
	import Introduction from './Introduction.svelte';
	import CustomFooter from './CustomFooter.svelte';
	import { Heading } from 'flowbite-svelte';
	import Studies from './Studies.svelte';
	import Skills from './Skills.svelte';
</script>

<div id='container'>
	<Heading tag="h1" class="mb-4" customSize="text-4xl font-bold  md:text-5xl lg:text-6xl">Bram Devlaminck</Heading>
	<Introduction/>
	<Skills/>
	<Studies/>
	<Experience/>
	<CustomFooter/>
</div>



<style>
    #container {
        max-width: 60em;
        margin: 2em auto auto;
    }
</style>
