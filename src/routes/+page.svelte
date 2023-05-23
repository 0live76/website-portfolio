<script>
  import Nav from "$lib/Nav.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<svelte:head>
  <title>Olive Roxburgh | Home</title>
</svelte:head>

<Nav />

<main>
  <h1 class="title">Olive Roxburgh</h1>
  <h2>Immersive, simple, and elegant website design.</h2>
  <p>Blah blah blah</p>
</main>

<img src="wave.svg" alt="" />

<Footer />

<style>
  h1 {
    text-align: left;
    font-size: 1050%;
    padding-bottom: 2%;
    font-family: "Tangerine", cursive;
    font-weight: lighter;
  }
  h2 {
    font-family: "Didact Gothic", sans-serif;
    font-size: 200%;
  }
  main {
    padding-left: 5%;
    padding-top: 10%;
  }

  img {
    margin-bottom: -2%;
  }
</style>
