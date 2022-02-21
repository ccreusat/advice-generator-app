<script lang="ts">
  import Advice from './lib/Advice.svelte';
</script>

<main>
  <Advice />
</main>

<style>
  :root {
    font-size: 62.5%;
    font-family: "Manrope", sans-serif;
    --light-cyan: hsl(193, 38%, 86%);
    --neon-green: hsl(150, 100%, 66%);
    --grayish-blue: hsl(217, 19%, 38%);
    --dark-grayish-blue: hsl(217, 19%, 24%);
    --dark-blue: hsl(218, 23%, 16%);
    --white: hsl(0, 0%, 100%);
  }
  main {
    min-height: 100vh;
    display: flex;
    place-items: center;
  }
</style>