<script>
	import { Heading } from 'flowbite-svelte';
</script>

<div class="p-8">
	<Heading tag='h2' customSize='text-4xl font-extrabold leading-loose'>Work Experience</Heading>

	<ol class="relative border-l border-gray-200 dark:border-gray-700">
		<li class="mb-10 ml-4">
			<div class="absolute w-3 h-3 bg-gray-200 rounded-full mt-1.5 -left-1.5 border border-white dark:border-gray-900 dark:bg-gray-700"></div>
			<time class="mb-1 text-sm font-normal leading-none text-gray-500 dark:text-gray-500">July - September 2023</time>
			<h3 class="text-lg font-semibold text-gray-900 dark:text-white"><a href='https://www.melexis.com/'>Internship at Melexis</a></h3>
			<p class="mb-4 text-base font-normal text-gray-500 dark:text-gray-400">
				During the summer of 2023, I did a 9 week long internship at <a href='https://www.melexis.com/' class="font-medium text-blue-600 dark:text-blue-500 hover:underline">Melexis</a>.
				This is a fabless semiconductor company located in Ypres (Belgium).
				My main focus was the development of microservices, with a strong emphasis on automated testing and deployment.
				The main technologies used during this time where Python and Kotlin in combination with Gitlab pipelines, Terraform and the Google Cloud Platform suite.
			</p>
		</li>
		<li class="mb-10 ml-4">
			<div class="absolute w-3 h-3 bg-gray-200 rounded-full mt-1.5 -left-1.5 border border-white dark:border-gray-900 dark:bg-gray-700"></div>
			<time class="mb-1 text-sm font-normal leading-none text-gray-500 dark:text-gray-500">August - September 2022</time>
			<h3 class="text-lg font-semibold text-gray-900 dark:text-white"><a href='https://dodona.be'>Software Developer at Dodona (Ghent University)</a></h3>
			<p class="mb-4 text-base font-normal text-gray-500 dark:text-gray-400">
				During this time I worked as a software engineer student for team <a href='https://dodona.be/' class="font-medium text-blue-600 dark:text-blue-500 hover:underline">Dodona</a>, lead by some of my professors at Ghent University.
				Dodona is a tool to help students learn to program. My main focus was on implementing small new features, various bugfixes and moving the source-code away from using JavaScript + JQuery towards <i>vanilla</i> TypeScript.</p>
		</li>
		<li class="mb-10 ml-4">
			<div class="absolute w-3 h-3 bg-gray-200 rounded-full mt-1.5 -left-1.5 border border-white dark:border-gray-900 dark:bg-gray-700"></div>
			<time class="mb-1 text-sm font-normal leading-none text-gray-500 dark:text-gray-500">July - August 2018</time>
			<h3 class="text-lg font-semibold text-gray-900 dark:text-white"><a href='https://www.verstraete.mcclabel.com/en'>Administrative job (MCC Verstraete)</a></h3>
			<p class="text-base font-normal text-gray-500 dark:text-gray-400">Here I worked as a student and did some administrative work that involved putting together files that were used later on in the product flow of this company.</p>
		</li>
	</ol>
</div>