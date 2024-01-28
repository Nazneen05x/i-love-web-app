<script>
  import Header from "../../lib/component/header.svelte";

  let isPopupVisible = false;

  function togglePopup() {
    isPopupVisible = !isPopupVisible;
  }
</script>

<Header />

<main>
    <section>
      <h2>CSS challenges</h2>
      <button on:click={togglePopup}>Lees meer</button>
      {#if isPopupVisible}
        <article class="cssbeschrijving cssbeschrijving-visibility">
          <span class="kruis" on:click={togglePopup}>x</span>
          <p class="cssp">Dit is een test of een pop-up verschijnt</p>
        </article>
      {/if}
    </section>
  </main>
  
  <style>
    .cssbeschrijving {
      display: none;
    }
  
    .cssbeschrijving-visibility {
      display: block;
    }
  </style>