<script>
  import Header from "../lib/component/header.svelte";
</script>

<Header />
<main>
  <section class="creamecolor">
    <img src="/keyboard.jpg" alt="spider-web" />
    <img class="mouse" src="/mouse.jpg" alt="mouse" />
  </section>

  <section class="bluecolor">
    <img class="speaker"  src="/speaker.jpg" alt="speaker">
  </section>
</main>

<style>
  .creamecolor {
    background-color: #f7dfdf;
    width: 15em;
    height: 25em;
    padding: 1em;
    margin: 1em;
    margin-left: 14em;
    margin-top: -0.5em;
    border-top-left-radius: 1em;
    border-bottom-left-radius: 1em;
  }

  img {
    width: 20em;
    height: auto;
    margin-left: -9em;
    border-radius: 2em;
    padding: 1em;
  }

  .mouse {
    margin-left: -15em;
  }

  .bluecolor{
    background-color: #9FD6E3;
    width: 15em;
    height: 25em;
    padding: 1em;
    margin: 1em;
    margin-left: -1em;
    margin-top: 8.5em;
    border-top-right-radius: 1em;
    border-bottom-right-radius: 1em;
    position: relative;
  }

  .speaker{
    margin-left: 2em;
    margin-top: 4em;
    width: 24em;
  }
</style>
