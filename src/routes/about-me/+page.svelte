<script>
  import Nav from "$lib/Nav.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<svelte:head>
  <title>Olive Roxburgh | About Me</title>
</svelte:head>
<Nav />
<main>
  <div class="columns">
    <div class="column">
      <h1>About Me</h1>
      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Debitis dolores consequatur perferendis voluptas. Quae aliquid culpa autem, ipsam a, est laudantium id fuga eligendi nihil eos reiciendis ad vel dolores?</p>
    </div>
    <div class="column">
      <img src="profile.png" alt="Profile" />
    </div>
  </div>
</main>
<Footer />

<style>
  h1 {
    text-align: left;
    font-size: 550%;
    padding-bottom: 2%;
    font-family: "Tangerine", cursive;
    font-weight: lighter;
  }

  main {
    padding-left: 4%;
    padding-top: 7%;
  }

  img {
    width: 40%;
    margin-left: 20%;
  }

  p {
    padding-left: 4%;
  }
</style>
