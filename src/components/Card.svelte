<script lang="ts">
  import Icon from "@iconify/svelte";
  let { src, title, detail, img_src, img_alt, tags, status} = $props();
</script>

<div class="card bg-base-100 max-w-sm shadow-lg">
 <figure>
    <img
      src={src}
      alt={img_alt} />
  </figure>
  <div class="card-body"> 
    <h2 class="card-title">
      {title}
      {#each status as s}
        {#if s}
          <div class="badge {`${s.color}`}">{s.title}</div>
        {/if}
      {/each}
    </h2>
    <p class="">{detail}</p>
    
    <div class="card-actions space-x-2 justify-end">
      <a href="https://github.com/kokejohh/pthipth" target="_blank" class="btn"><Icon icon="octicon:logo-github-16" width="45" height="16" /></a>
      <button class="btn btn-accent">Visit</button>
    </div>
 
    <div class="card-actions justify-end">
      {#each tags as tag}
        <div class="badge badge-outline">{tag}</div>
      {/each}
    </div>
  </div>
</div>