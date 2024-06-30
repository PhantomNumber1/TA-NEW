<script>
	import Nav from './lib/components/NavBar.svelte';
	import Foo from './lib/components/Reserve.svelte';
  </script>
  
  <Nav />
  
  <main>
	<h1>Welcome to MySite</h1>
	<section id="home">Home Content</section>
	<section id="about">About Content</section>
	<section id="services">Services Content</section>
	<section id="contact">Contact Content</section>
  </main>

  <Foo />
  
  <style>
	main {
	  padding: 20rem;
	}
  
	section {
	  margin: 2rem 0;
	}
  </style>
  