<script lang="ts">
  import "../app.css";
  import "../fonts.css";
  let { children } = $props();
</script>

<div class="app">
  <main>
    {@render children()}
  </main>
  <footer></footer>
</div>
