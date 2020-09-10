<script>
  import Button from "./Button.svelte";
  import Navbar from "./Navbar.svelte";

  let nama = "nisa";
</script>

<style>
  main {
    font-family: sans-serif;
    text-align: center;
  }
</style>

<main>
<Navbar />
<p>Lorem ipsum {nama} sit amet consectetur, adipisicing elit. Facere fugit, consectetur ea magni quidem nihil iste sed esse tempore, non enim aliquid pariatur eius itaque cumque quam magnam ullam maiores.</p>
	<Button />
</main>