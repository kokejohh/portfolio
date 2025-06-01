<script lang="ts">
    const { children } = $props();

</script>

<div class="flex flex-row flex-wrap space-y-2 space-x-2">
    {@render children()}
</div>