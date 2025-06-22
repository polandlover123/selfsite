<div class="container">
  <div class="title">
    <img alt="polandlover.tech" src="/poland.png">
  </div>
  <div class="buttons">
    <div class="github">
      <a href="https://github.com/polandlover123">
        <img src="/github.png" on:mouseover={(e) => e.target.src = '/github_hover.png'} on:mouseout={(e) => e.target.src = '/github.png'} on:click={() => window.location.href = '/'}>

      </a>
      <script>
        let currentSrc = '/github.png';
      
        function handleMouseOver(e) {
          currentSrc = '/github_hover.png';
        }
        function handleMouseOut(e) {
          currentSrc = '/github.png';
        }
      </script>
    </div>
  </div>
</div>


