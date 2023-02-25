<script>
	import { Heading, Img, P } from 'flowbite-svelte';
</script>

<div id='left-spacer'>
	<div id='title-div'>
		<Heading tag="h1" class="mb-4" customSize="text-6xl font-bold">Bram Devlaminck</Heading>
	</div>
<div id='wrapper'>

	<div id='textDiv'>
		<P align='justify' size='lg' weight='medium' height='relaxed' justify>
			Hi, I'm Bram and I'm currently working on my Masters degree in computer science at Ghent University.
			I'm very passionate about how technology can improve peoples life and am currently looking for an internship for
			the summer of 2023.
			Thanks to my education I have a broad base knowledge in a lot of different IT-disciplines.
			Transforming this theoretical knowledge into practice is what I am currently looking most forward to.
		</P>
	</div>
	<div id='imgDiv'>
		<Img size='max-w-full' imgClass='h-auto' class='rounded-lg' src='picture_profile.jpg' alt='Profile picture of Bram Devlaminck' />
	</div>
</div>
</div>

<style>
    #imgDiv {
				width: 27em;
				margin-top: 1em;
        margin-right: 0.5em;
        margin-left: 0.5em;
    }

    #wrapper {
				margin: auto;
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
    }

    #textDiv {
				width: 27em;
        margin-right: 0.5em;
        margin-left: 0.5em;
        margin-top: 0.5em;
    }

		#left-spacer {
        padding-left: 2em;
				padding-right: 2em;

    }
</style>