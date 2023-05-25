<script>
  import Nav from "$lib/Nav.svelte"
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

  footer {
    font-family: "Didact Gothic", sans-serif;
    background-color: black;
    padding-top: 2%;
    padding-right: 2%;
    font-size: 160%;
    padding-bottom: 2%;
    color: white;
    font-weight: bold;
    text-align: right;
    margin-bottom: 0;
  }
</style>
