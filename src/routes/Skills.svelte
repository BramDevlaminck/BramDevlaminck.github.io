<script>
	import { Heading } from 'flowbite-svelte';
	import { Tooltip } from 'flowbite-svelte';
</script>

<div class='p-8'>
	<Heading tag='h2' customSize='text-4xl font-extrabold leading-loose'>Skills</Heading>
	<div class='cards-container'>
		<div class='max-w-sm overflow-hidden shadow-lg border rounded-lg card-wrapper'>
			<h5 class='mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white'>Programming languages</h5>
			<p class='font-normal text-gray-700 dark:text-gray-400 leading-tight'>
				I'm mostly familiar with these languages from the projects I've created for the courses I follow at Ghent
				University.
			</p>
			<div class='container'>
				<img src='java.svg' class='skill' alt='Java logo' />
				<Tooltip>Java</Tooltip>
				<img src='python.png' class='skill' alt='Python logo' />
				<Tooltip>Python</Tooltip>
				<img src='Kotlin_Icon.svg' class='skill' alt='Kotlin logo' />
				<Tooltip>Kotlin</Tooltip>
				<img src='C_Programming_Language.svg' class='skill' alt='C logo' />
				<Tooltip>C</Tooltip>
				<img src='ISO_C++_Logo.svg' class='skill' alt='C++ logo' />
				<Tooltip>C++</Tooltip>
				<img src='JavaScript.png' class='skill' alt='JavaScript logo' />
				<Tooltip>JavaScript</Tooltip>
				<img src='Typescript_logo_2020.svg' class='skill' alt='TypeScript logo' />
				<Tooltip>TypeScript</Tooltip>
				<img src='html-5.png' class='skill' alt='HTML-5 logo' />
				<Tooltip>HTML</Tooltip>
				<img src='css-3.png' class='skill' alt='CSS-3 logo' />
				<Tooltip>CSS</Tooltip>
				<img src='sql.svg' class='skill' alt='SQL logo' />
				<Tooltip>SQL</Tooltip>
				<img src='haskell.png' class='skill' alt='Haskell logo' />
				<Tooltip>Haskell</Tooltip>
				<img src='prolog.webp' class='skill' alt='Prolog logo' />
				<Tooltip>Prolog</Tooltip>
			</div>
		</div>

		<div class='max-w-sm overflow-hidden shadow-lg border rounded-lg card-wrapper'>
			<h5 class='mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white'>Technologies</h5>
			<p class='font-normal text-gray-700 dark:text-gray-400 leading-tight'>
				These come in handy during the development cycle to optimize the development experience, write reports,
				effectively collaborate with collegues,...
			</p>
			<div class='container'>
				<img src='docker.png' class='skill' alt='Docker logo' />
				<Tooltip>Docker</Tooltip>
				<img src='Git_icon.svg' class='skill' alt='GIT logo' />
				<Tooltip>GIT</Tooltip>
				<img src='markdown.svg' class='skill' alt='Markdown logo' />
				<Tooltip>Markdown</Tooltip>
				<img src='latex.svg' class='skill' alt='LaTeX logo' />
				<Tooltip>LaTeX</Tooltip>
				<img src='linux.png' class='skill' alt='Linux logo' />
				<Tooltip>Linux</Tooltip>
			</div>
		</div>

		<div class='max-w-sm overflow-hidden shadow-lg border rounded-lg card-wrapper'>
			<h5 class='mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white'>Soft Skills</h5>
			<p class='font-normal text-gray-700 dark:text-gray-400 leading-tight'>
				Dit is een lege tekst die verder nog ingevuld moet worden met enkele soft-skills. Hierin toon ik dat ik meer ben
				dan enkel iemand die kan programmeren
			</p>
		</div>

		<div class='max-w-sm overflow-hidden shadow-lg border rounded-lg card-wrapper'>
			<h5 class='mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white'>Development Environments</h5>
			<p class='font-normal text-gray-700 dark:text-gray-400 leading-tight'>
				For development of own projects I'm mostly using following IDEs.
			</p>
			<div class='container'>
				<img src='PyCharm_Icon.svg' class='skill' alt='PyCharm logo' />
				<Tooltip>PyCharm</Tooltip>
				<img src='WebStorm_Icon.svg' class='skill' alt='WebStorm logo' />
				<Tooltip>WebStorm</Tooltip>
				<img src='Clion.svg' class='skill' alt='Clion logo' />
				<Tooltip>Clion</Tooltip>
				<img src='IntelliJ_IDEA_Icon.svg' class='skill' alt='IntelliJ IDEA logo' />
				<Tooltip>IntelliJ IDEA</Tooltip>
				<img src='vscode.svg' class='skill' alt='Visual Studio Code logo' />
				<Tooltip>Visual Studio Code</Tooltip>
			</div>
		</div>
	</div>
</div>


<style>
    .card-wrapper {
        alignment: center;
        padding: 1em;
        margin: 1em auto 1em auto;
        transition: transform .2s;
    }

    .card-wrapper:hover {
        transform: scale(1.05);
    }

    .cards-container {
        display: flex;
        flex-wrap: wrap;
        justify-content: flex-start;
        align-items: stretch;
        height: 100%;
    }

    .skill {
        height: 2.3em;
        width: 2.3em;
        padding: 0.2em;
        float: left;
    }

		.container {
				margin: 0.3em 0 0 0;
		}
</style>