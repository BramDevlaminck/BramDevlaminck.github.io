<script>
	import { Card } from 'flowbite-svelte';
	import { Tooltip } from 'flowbite-svelte';
</script>

<Card>
	<h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Technical Skills</h5>
	<p class="font-normal text-gray-700 dark:text-gray-400 leading-tight">
		These are the languages I'm familiar with, mainly from the projects I've created for the courses I follow.
	</p>
	<div class='container'>
		<img src='java.svg' class='skill' alt='Java logo' />
		<Tooltip>Java</Tooltip>
		<img src='python.png' class='skill' alt='Python logo'/>
		<Tooltip>Python</Tooltip>
		<img src='Kotlin_Icon.svg' class='skill' alt='Kotlin logo'/>
		<Tooltip>Kotlin</Tooltip>
		<img src='C_Programming_Language.svg' class='skill' alt='C logo'/>
		<Tooltip>C</Tooltip>
		<img src='ISO_C++_Logo.svg' class='skill' alt='C++ logo'/>
		<Tooltip>C++</Tooltip>
		<img src='JavaScript.png' class='skill' alt='JavaScript logo'/>
		<Tooltip>JavaScript</Tooltip>
		<img src='Typescript_logo_2020.svg' class='skill' alt='TypeScript logo'/>
		<Tooltip>TypeScript</Tooltip>
		<img src='html-5.png' class='skill' alt='HTML-5 logo'/>
		<Tooltip>HTML</Tooltip>
		<img src='css-3.png' class='skill' alt='CSS-3 logo'/>
		<Tooltip>CSS</Tooltip>
		<img src='sql.svg' class='skill' alt='SQL logo'/>
		<Tooltip>SQL</Tooltip>
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