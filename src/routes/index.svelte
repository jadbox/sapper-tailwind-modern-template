<script>

</script>

<style>
  h1,
  figure,
  p {
    text-align: center;
    margin: 0 auto;
  }

  h2 {
    font-size: 2.8em;
    text-transform: uppercase;
    font-weight: 700;
    margin: 0 0 0.5em 0;
  }

  figure {
    margin: 0 0 1em 0;
  }

  p {
    margin: 1em auto;
  }

  @media (min-width: 480px) {
    h1 {
      font-size: 4em;
    }
  }
</style>

<svelte:head>
<title>Sapper project template</title>
</svelte:head>

<h1 class="text-gray-800 uppercase font-bold mb-4">Great success!</h1>

<figure class="items-center w-full">
  <img class="max-w-xl m-auto w-4/5" alt="Success Kid" src="successkid.jpg" />
  <figcaption>Have fun with Sapper!</figcaption>
</figure>

<p>
  <strong>Try editing this file (src/routes/index.svelte) to test live reloading.</strong>
</p>
