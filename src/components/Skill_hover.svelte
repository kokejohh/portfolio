<script lang="ts">
    import Icon from '@iconify/svelte';

    let {text, icon_class} = $props();
</script>

<div class="tooltip">
    <div class="tooltip-content">
        <div class="text-primary font-black">{text}</div>
    </div>
    <Icon icon={`${icon_class}`} width="36" height="36" />
</div>