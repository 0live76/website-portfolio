<script>
  import { page } from "$app/stores"
</script>

<nav>
  <a href="/" class:current-page={$page.url.pathname == "/"}>Home</a>
  <a href="about-me" class:current-page={$page.url.pathname.includes("about-me")}>About Me</a>
  <a href="portfolio" class:current-page={$page.url.pathname.includes("portfolio")}>My Portfolio</a>
</nav>

<style>
  nav {
    padding-top: 2%;
    padding-left: 2%;
    padding-bottom: 2%;
    display: flex;
    justify-content: space-between;
    padding-right: 60%;
    width: 100%;
    background-color: white;
    position: fixed;
  }

  a {
    font-size: 130%;
    color: black;
    font-family: "Didact Gothic", sans-serif;
    text-transform: uppercase;
  }
  a:hover {
    font-weight: bold;
    font-style: italic;
  }

  .current-page {
    font-weight: bold;
    font-style: italic;
  }
</style>
