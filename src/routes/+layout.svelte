<script lang="ts">
  import "victormono";
  import "../app.css";
  import { injectAnalytics } from '@vercel/analytics/sveltekit'
  let { children } = $props();
  injectAnalytics({ mode: dev ? 'development' : 'production' });
</script>

<div class="app">
  <main>
    {@render children()}
  </main>
</div>
