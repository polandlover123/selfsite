<script lang="ts">
  import "victormono";
  import "../app.css";
  let { children } = $props();
</script>

<div class="app">
  <main>
    {@render children()}
  </main>
  <footer></footer>
</div>
