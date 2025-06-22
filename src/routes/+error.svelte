<div class="errorcontainer">
  <img src="/404.png" on:mouseover={(e) => e.target.src = '/404_hover.png'} on:mouseout={(e) => e.target.src = '/404.png'} on:click={() => window.location.href = '/'}>
</div>

<script>
  let currentSrc = '/404.png';

  function handleMouseOver(e) {
    currentSrc = '/404_hover.png';
  }
  function handleMouseOut(e) {
    currentSrc = '/404.png';
  }
</script>
<style>
  :root {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height:100vh
  }
  h1 {
    color: #151515;
  }
  a {
    color: #151515;
    font-size: 1rem;
    padding: 0.5rem 1rem;
  }
</style>