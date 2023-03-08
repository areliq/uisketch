<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<style>
  :root {
    background-color: antiquewhite;
    --measure: 60em;
  }

  :global(*) {
    max-width: var(--measure);
  }

  :global(html, body, div, header, nav, main, footer) {
    max-width: none;
  }
</style>
