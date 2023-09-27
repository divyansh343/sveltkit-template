<script>
	import '../app.css';
	import Footer from '../lib/Footer.svelte';
	import Navbar from '../lib/Navbar.svelte';
  let theme = "dracula"
</script>

<div data-theme={theme}>
	<Navbar {theme} />
	<slot />
	<Footer />
</div>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Prompt&family=Questrial&display=swap');
</style>