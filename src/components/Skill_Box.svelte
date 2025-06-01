<script lang="ts">
    const { children, title, position} = $props();

    const positionClass: string = position === 'left' ?
                            'lg:col-start-1 lg:col-end-4' :
                            'lg:col-start-4 lg:col-end-7';
</script>

<div class="flex flex-col {positionClass}" >
    <p>{title}</p>
    <div class="flex flex-row flex-wrap space-y-2 space-x-2">
        {@render children()}
    </div>
</div>