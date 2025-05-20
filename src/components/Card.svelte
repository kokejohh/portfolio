<script lang="ts">
  let { src = "https://media.tenor.com/Dh7CxUiogBMAAAAm/vev-veve.webp", title, detail, img_alt, tags, status, link_github, link_web} = $props();
</script>

<div class="card bg-base-100 max-w-sm shadow-lg hover:bg-base-200">
  <div class="card-body space-y-2">
    <figure>
      <img
        src={src}
        alt={img_alt} />
    </figure>
 <div class="card-title text-2xl">
      {title}
      {#each status as s}
        {#if s}
          <div class="badge {`${s.color}`}">{s.title}</div>
        {/if}
      {/each}
    </div>
    <p class="">{detail}</p>
    
    <div class="card-actions space-x-2 justify-end">
      {#if link_github}
        <a href={link_github} target="_blank" class="btn btn-error text-base-100">Github</a>
      {/if}
      {#if link_web}
        <a href={link_web} target="_blank" class="btn btn-accent text-base-100">Visit</a>
      {/if}
    </div>
 
    <div class="card-actions justify-end">
      {#each tags as tag}
        <div class="badge badge-outline">{tag}</div>
      {/each}
    </div>
  </div>
</div>