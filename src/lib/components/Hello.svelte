<script>
    let name = $state('world');
</script>
{#if name === 'world'}
<h1 class="text-4xl text-center text-blue-500">Hello {name}!</h1>
{:else}
 <h1 class="text-4xl">I don't say hello to anyone else</h1>
{/if}
