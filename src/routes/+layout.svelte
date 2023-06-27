<script>
  import "../app.postcss";
</script>

<slot />

<style>
  @import url('https://fonts.googleapis.com/css2?family=Outfit:wght@500&display=swap');
  :global(body) {
    background-color: #eeeded;
    font-family: 'Outfit', sans-serif;
    color: rgb(39, 39, 39);
  }
</style>
