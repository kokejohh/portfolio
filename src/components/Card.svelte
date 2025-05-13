<script lang="ts">
  let { src, title, detail, img_src, img_alt, tags, status, link_github, link_web} = $props();
</script>

<div class="card bg-base-100 max-w-sm shadow-lg hover:bg-base-200">
  <div class="card-body space-y-2">
    <div class="card-title text-2xl">
      {title}
      {#each status as s}
        {#if s}
          <div class="badge {`${s.color}`}">{s.title}</div>
        {/if}
      {/each}
    </div>

    <figure>
      <img
        src={src}
        alt={img_alt} />
    </figure>

    <p class="">{detail}</p>
    
    <div class="card-actions space-x-2 justify-end">
      {#if link_github}
        <a href={link_github} target="_blank" class="btn btn-error">Github</a>
      {/if}
      {#if link_web}
        <a href={link_web} target="_blank" class="btn btn-accent">Visit</a>
      {/if}
    </div>
 
    <div class="card-actions justify-end">
      {#each tags as tag}
        <div class="badge badge-outline">{tag}</div>
      {/each}
    </div>
  </div>
</div>