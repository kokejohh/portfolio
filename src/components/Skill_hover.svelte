<script lang="ts">
    import Icon from '@iconify/svelte';

    let {text, icon_class} = $props();
</script>

<div class="tooltip">
    <div class="tooltip-content">
        <div class="animate-bounce text-primary font-black">{text}</div>
    </div>
    <Icon icon={`${icon_class}`} width="48" height="48" />
</div>