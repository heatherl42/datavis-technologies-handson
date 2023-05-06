<script>
  let current = "";
</script>

<style>
  .selected {
    background-color:blue
  }
</style>

<!-- We will cover buttons later on! -->
<button class="btn btn-secondary {current === "messi" ? 'selected': ''}" on:click={() => (current = "messi")}>
  Messi
</button>

<button class="btn btn-secondary {current ==="ronaldo" ? 'selected': ''}" on:click={() => (current = "ronaldo")}>
  Ronaldo
</button>

<button class="btn btn-secondary {current ==="neymar" ? 'selected': ''}" on:click={() => (current = "neymar")}>
  Neymar
</button>
