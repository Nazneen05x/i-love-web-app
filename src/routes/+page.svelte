<script>
  import Header from "../lib/component/header.svelte";
</script>

<Header />
<main>
  <section class="creamecolor">
    <img src="/keyboard.jpg" alt="spider-web" />
    <button class="Challenges">
      <a href="/challenges">Challenges</a>
    </button>
  </section>

  <section>
    <img class="mouse" src="/mouse.jpg" alt="mouse" />
    <button class="meetup">
      <a href="/meetup">Meet up</a>
    </button>
  </section>

  <section class="bluecolor">
    <img class="speaker" src="/speaker.jpg" alt="speaker" />
    <button class="loveweb">
      <a href="/weloveweb">We love web</a>
    </button>
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

  .Challenges {
    margin-top: 13em;
    padding: 1em;
    position: absolute;
  }

  .meetup {
    margin-top: 2em;
    padding: 1em;
    position: absolute;
  }

  .loveweb {
    padding: 1em;
    margin-left: 6em;
    top: -6em;
    position: relative;
  }

  button {
    background-color: white;
    border-radius: 0.5em;
    padding: 0.5em;
    margin-left: -24em;
    border: none;
  }

  a{
    text-decoration: none;
  }

  .mouse {
    margin-left: 6em;
    margin-top: -11em;
  }

  .bluecolor {
    background-color: #9fd6e3;
    width: 15em;
    height: 25em;
    padding: 1em;
    margin: 1em;
    margin-left: -1em;
    margin-top: 2.5em;
    border-top-right-radius: 1em;
    border-bottom-right-radius: 1em;
    position: relative;
  }

  .speaker {
    margin-left: 2em;
    margin-top: 4em;
    width: 24em;
  }
</style>
