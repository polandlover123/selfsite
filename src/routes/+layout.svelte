<script lang="ts">
  import "../app.css";
  let { children } = $props();
  import "@fontsource-variable/victor-mono";
</script>

<div class="app">
  <main>
    {@render children()}
  </main>
  <footer></footer>
</div>
