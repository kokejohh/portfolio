<script>
    import Card from "./Card.svelte";

    import pthipth from "$lib/images/pthipth.jpeg";
    import valentines_day from "$lib/images/valentines_day.jpeg";
    import loveme from "$lib/images/loveme.jpeg";
    import pichit300 from "$lib/images/pichit300.jpeg";
    import rov_supernova from "$lib/images/rov_supernova.jpeg";
    import todolist from "$lib/images/todolist.jpeg";
</script>

<article id="projects" class="prose lg:mt-8 scroll-mt-20">
    <h1>Projects</h1>
</article>

<ul class="menu menu-horizontal p-8 lg:p-16 grid grid-cols-1 gap-1 lg:grid-cols-2 lg:gap-8">
    <Card src={pthipth} title="pthipth" detail="Thread Library" tags={["Final Year Project", "C","Library", "Thread"]} status={[{title: "Library", color:"badge-secondary"}]} link_github="https://github.com/kokejohh/pthipth"/>
    <Card  title="portfolio" detail="Website portfolio" tags={["Svelte", "TypeScript", "DaisyUI"]} status={[{title: "Website", color: "badge-primary"}]} link_github="https://github.com/kokejohh/portfolio"/>
    <Card src={valentines_day} title="valentine-day" detail="" tags={["JavaScript", "HTML", "CSS"]} status={[{title: "Website", color: "badge-primary"}]} link_github="https://github.com/kokejohh/valentine-day" link_web="https://kokejohh.github.io/valentine-day/"/>
    <Card src={loveme} title="loveme" detail="" tags={["Javascript", "HTML", "CSS"]} status={[{title: "Website", color: "badge-primary"}]} link_github="https://github.com/kokejohh/loveme" link_web="https://kokejohh.github.io/loveme/"/>
    <Card src={pichit300} title="pichit300" detail="" tags={["Javascript", "HTML", "CSS"]} status={[{title: "Website", color: "badge-primary"}]} link_github="https://github.com/kokejohh/pichit300" link_web="https://kokejohh.github.io/pichit300/src/"/>
    <Card src={rov_supernova} title="rov supernova" detail="" tags={["Svelte", "JavaScript", "TailwindCSS"]} status={[{title: "Website", color: "badge-primary"}]} link_github="https://github.com/kokejohh/rov_supernova" link_web="https://kokejohh.github.io/rov_supernova/src/main.html"/>
    <Card src={todolist} title="todolist" detail="" tags={["JavaScript", "HTML", "CSS"]} status={[{title: "Website", color: "badge-primary"}]} link_github="https://github.com/kokejohh/project_todolist" link_web="https://kokejohh.github.io/project_todolist/"/>
    <Card title="Gloden pool" detail="" tags={["Unity", "C#"]} status={[{title: "Game", color: "badge-warning"}]} link_web="https://www.youtube.com/watch?v=O8_jTC1FPo4"/>
    <Card title="Catguins 2D" detail="" tags={["Unity", "C#"]} status={[{title: "Game", color: "badge-warning"}]} link_web="https://gamejolt.com/games/catguins2d/203049"/>
    <Card title="Registration" detail="" tags={["Node.js", "Express.js", "HTML", "Bootstrap"]} status={[{title: "Website", color: "badge-primary"}]}/>
    <Card title="Purrfect" detail="" tags={["PHP", "HTML", "CSS", "Bootsrap", "TailwindCSS", "MySQL"]} status={[{title: "Website", color: "badge-primary"}]}/>
</ul>