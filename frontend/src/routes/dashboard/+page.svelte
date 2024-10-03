<script>
    import { onMount } from 'svelte';
    import { models, Embed } from 'powerbi-client';

    let embedUrl = 'YOUR_EMBED_URL';
    let accessToken = 'YOUR_ACCESS_TOKEN';
    let embedContainer;
</script>
<div>
    <h1 class="text-4xl font-bold">Dashboard</h1>
</div>