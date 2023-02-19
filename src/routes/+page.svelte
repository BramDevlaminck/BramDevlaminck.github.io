<script>
	import Experience from './Experience.svelte';
	import Introduction from './Introduction.svelte';
	import CustomFooter from './CustomFooter.svelte';
</script>

<div id='container'>
	<Introduction/>
	<Experience/>
	<CustomFooter/>
</div>



<style>
    #container {
        max-width: 60em;
        margin: 2em auto auto;
    }
</style>
