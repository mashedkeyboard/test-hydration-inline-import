<script>
    import something from '../test.scss?inline';
</script>

<svelte:head>
    <svelte:element this={'style'} type="text/css">{something}</svelte:element>
</svelte:head>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>
