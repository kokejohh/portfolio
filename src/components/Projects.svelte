<script>
    import Card from "./Card.svelte";
</script>

<article id="projects" class="prose scroll-mt-24">
    <h1>Projects</h1>
</article>
<ul class="menu menu-horizontal lg:p-16 grid grid-cols-1 gap-1 lg:grid-cols-2 lg:gap-8">
    <Card src="https://img.daisyui.com/images/stock/photo-1606107557195-0e29a4b5b4aa.webp" title="pthipth" detail="Thread Library" tags={["Final Year Project", "C","Library", "Thread"]} status={[{title: "Library", color:"badge-secondary"}]} />
    <Card title="portfolio" detail="" tags={["Svelte", "TypeScript", "DaisyUI"]} status={[{title: "Website", color: "badge-primary"}]}/>
    <Card title="valentine-day" detail="" tags={["JavaScript", "HTML", "CSS"]} status={[{title: "Website", color: "badge-primary"}]}/>
    <Card title="loveme" detail="" tags={["Javascript", "HTML", "CSS"]} status={[{title: "Website", color: "badge-primary"}]}/>
    <Card title="pichit300" detail="" tags={["Javascript", "HTML", "CSS"]} status={[{title: "Website", color: "badge-primary"}]}/>
    <Card title="rov supernova" detail="" tags={["Svelte", "JavaScript", "TailwindCSS"]} status={[{title: "Website", color: "badge-primary"}]}/>
    <Card title="todolist" detail="" tags={["JavaScript", "HTML", "CSS"]} status={[{title: "Website", color: "badge-primary"}]}/>
    <Card title="Gloden pool" detail="" tags={["Unity", "C#"]} status={[{title: "Game", color: "badge-accent"}]}/>
    <Card title="Catguins 2D" detail="" tags={["Unity", "C#"]} status={[{title: "Game", color: "badge-accent"}]}/>
    <Card title="Registration" detail="" tags={["Node.js", "Express.js", "HTML", "Bootstrap"]} status={[{title: "Website", color: "badge-primary"}]}/>
    <Card title="Purrfect" detail="" tags={["PHP", "HTML", "CSS", "Bootsrap", "TailwindCSS", "MySQL"]} status={[{title: "Website", color: "badge-primary"}]}/>
</ul>