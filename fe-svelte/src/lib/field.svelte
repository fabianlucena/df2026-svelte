<script>
  let { children, label } = $props();
</script>

<fieldset>
<legend> {label}</legend> 
  {@render  children()}
</fieldset>
