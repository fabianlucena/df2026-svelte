<script>
  import TextField from './textfield.svelte';

  let { label, value = $bindable('')  } = $props();
</script>

<TextField {label} type="password" bind:value />
