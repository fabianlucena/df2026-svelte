<script>
  import Field from './field.svelte';

  let { label, type = "text", value = $bindable('') } = $props();
</script>

<Field {label}>
  <input {type} bind:value >
</Field> 
