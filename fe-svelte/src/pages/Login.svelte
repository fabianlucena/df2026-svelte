<script>
  import Form from '../lib/form.svelte';
  import TextField from '../lib/textfield.svelte';
  import SecretField from '../lib/secretField.svelte';

  let username = $state('');
  let password = $state('');
</script>

<Form>
  {username} - {password}

  <TextField label="Nombre de usuario" bind:value={username} />
  <SecretField label="Contraseña" bind:value={password} />

</Form>