<script>
  let { children } = $props();
</script>

<form>
  {@render  children()}

  <button type="submit">
    Ingresar
  </button>
</form>
