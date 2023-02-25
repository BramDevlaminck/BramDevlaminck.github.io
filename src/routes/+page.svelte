<script>
	import Experience from './Experience.svelte';
	import Introduction from './Introduction.svelte';
	import CustomFooter from './CustomFooter.svelte';
	import Studies from './Studies.svelte';
	import Skills from './Skills.svelte';
</script>

<title>Online resume/CV of Bram Devlaminck</title>
<meta name='description' content='Online Resume Bram Devaminck. A clean overview of my skills, studies and experiences'>
<div id='container'>
	<Introduction/>
	<Skills/>
	<Studies/>
	<Experience/>
	<CustomFooter/>
</div>



<style>
    #container {
        max-width: 60em;
        margin: 2em auto auto auto;
    }
</style>
