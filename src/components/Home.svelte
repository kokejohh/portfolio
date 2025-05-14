<script lang="ts">
    import Icon from "@iconify/svelte";
    import me from "$lib/images/me.jpeg";
    import me_light from "$lib/images/me-light.jpg";
    import { themeDark } from "../stores/theme";
    import { onMount } from "svelte";

    let showPicture: boolean = false;
    let onloading: boolean = true;

    onMount(() => {
      setTimeout(() => {
        onloading = false;
        setTimeout(() => {
          showPicture = true;
        }, 100);
      }, 1000);
    });
    
</script>
<div id="home" class="p-8 lg:pr-32 hero bg-base-100 min-h-screen">
  <div class="hero-content flex-col lg:flex-row">
    {#if !showPicture}
      <div class="{onloading ? "" : "hidden "} skeleton shadow-2xl h-64 min-w-64 max-w-3xs mask mask-squircle"></div>
    {/if}
      <img
        alt="me"
        class:opacity-100={showPicture}
        src={$themeDark ? me : me_light}
        class="{onloading ? "hidden " : ""} opacity-0 transition-opacity duration-700 shadow-2xl min-w-64 max-w-3xs mask mask-squircle"
      />
  
    <div>
      <h1 class="text-2xl lg:text-4xl font-bold mt-2">Pitchakorn Thiprangsi <Icon class="inline" icon="flagpack:th" width="32" height="24" /></h1>
      
      <p class="py-6 text-lg">
        I'm passionate about computers and coding, and I aspire to create something extraordinary. I'm eager to gain a comprehensive understanding of programming.
        I have a diverse skill set, including basic knowledge in front-end, back-end, and game development. However, I never stop seeking knowledge.
      </p>
     
    </div>  
  </div>

</div>