<script>
	import { Img, P } from 'flowbite-svelte';
</script>
<div id='wrapper'>
	<div id='textDiv'>
		<P align='justify'>Hi, I'm Bram Devlaminck and I'm currently working on my Masters degree in computer science at Ghent University. I'm very passionate about how technology can improve peoples life.
		</P>
	</div>
	<div id='imgDiv'>
		<Img size="max-w-md" class="rounded-lg" src="picture_profile.jpg" alt="Profile picture of Bram Devlaminck" />
	</div>
</div>


<style>
	#imgDiv {
			width: 20em;
      margin: 0.5em 0.5em 0.0em auto;
  }
  #wrapper {
      display: flex;
      flex-wrap: wrap;
      justify-content: flex-start;
  }
  #textDiv {
			max-width: 25em;
  }
</style>