<script>
	import { Card, Img } from 'flowbite-svelte';
</script>

<Card>
	<h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Technical Skills</h5>
	<p class="font-normal text-gray-700 dark:text-gray-400 leading-tight">
		These are the languages I'm familiar with, mainly from the projects I've created for the courses I follow.
	</p>
	<div class='container'>
		<img src='java.svg' class='skill' alt='Java logo' />
		<img src='python.png' class='skill' alt='Python logo'/>
		<img src='Kotlin_Icon.svg' class='skill' alt='Kotlin logo'/>
		<img src='C_Programming_Language.svg' class='skill' alt='C logo'/>
		<img src='ISO_C++_Logo.svg' class='skill' alt='C++ logo'/>
		<img src='JavaScript.png' class='skill' alt='Javascript logo'/>
		<img src='Typescript_logo_2020.svg' class='skill' alt='Typescript logo'/>
	</div>

</Card>

<style>
	.skill {
			height: 2.3em;
			width: 2.3em;
			padding: 0.2em;
			float: left;
	}
</style>