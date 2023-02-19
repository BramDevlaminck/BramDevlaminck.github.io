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
			width: 30em;
      margin: 0.5em 0.5em 0.0em auto;
			overflow: hidden;
  }
  #wrapper {
      width: 60em;
      overflow: hidden; /* will contain if #first is longer than #second */
  }
  #textDiv {
      width: 30em;
      float:left; /* add this */
  }
</style>