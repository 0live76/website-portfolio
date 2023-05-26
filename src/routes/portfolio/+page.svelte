<script>
  import Nav from "$lib/Nav.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<svelte:head>
  <title>Olive Roxburgh | Portfolio</title>
</svelte:head>
<Nav />
<main>
  <h1>Portfolio</h1>
  <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Debitis dolores consequatur perferendis voluptas. Quae aliquid culpa autem, ipsam a, est laudantium id fuga eligendi nihil eos reiciendis ad vel dolores?</p>

  <div class="columns">
    <div class="column">
      <img src="sunburst1.png" alt="" />
    </div>
    <div class="column">
      <h2>Sunburst Music Festival</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nam accusamus fugit quibusdam, et beatae suscipit quisquam aliquam molestias reprehenderit voluptatem consectetur, aspernatur possimus nisi dolores ut asperiores sequi. Eum, eligendi?</p>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim debitis hic sint vero quaerat sed, vel provident labore quas incidunt nostrum tempore, doloremque accusantium! Nesciunt reiciendis quae eos suscipit velit.</p>
      <a href="https://music-festival-assessment-0live76.vercel.app/">– Visit</a>
    </div>
  </div>

  <div class="center">
    <p>My designs are optimized for mobile layout.</p>
    <img src="mobile.png" alt="" />
  </div>

  <div class="columns second">
    <div class="column">
      <h2>Class Portfolio</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nam accusamus fugit quibusdam, et beatae suscipit quisquam aliquam molestias reprehenderit voluptatem consectetur, aspernatur possimus nisi dolores ut asperiores sequi. Eum, eligendi?</p>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim debitis hic sint vero quaerat sed, vel provident labore quas incidunt nostrum tempore, doloremque accusantium! Nesciunt reiciendis quae eos suscipit velit.</p>
      <a href="https://github.com/craighead-diocesan-school/assessment-class-profile-0live76">– Visit</a>
    </div>
    <div class="column">
      <img src="dummi1.png" alt="" />
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
    padding-right: 4%;
  }

  h2 {
    font-size: 190%;
    font-family: "Didact Gothic", sans-serif;
    padding-bottom: 3%;
  }

  a {
    color: rgb(32, 96, 124);
    font-size: 120%;
    font-family: "Didact Gothic", sans-serif;
  }

  a:hover {
    font-style: italic;
  }

  p {
    padding-bottom: 3%;
  }

  .second {
    padding-top: 6%;
  }

  .center {
    text-align: center;
    padding: 5%;
  }
</style>
