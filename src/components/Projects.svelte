<script>
    import Card from "./Card.svelte";

    import pthipth from "$lib/images/pthipth.jpeg";
    import koke_theme from "$lib/images/koke-theme.png";
    import portfolio from "$lib/images/porfolio.jpeg";
    import valentines_day from "$lib/images/valentines_day.jpeg";
    import loveme from "$lib/images/loveme.jpeg";
    import hostpital from "$lib/images/hospital.png";
    import pichit300 from "$lib/images/pichit300.jpeg";
    import rush_discovery from "$lib/images/rush_discovery.jpeg";
    import rov_supernova from "$lib/images/rov_supernova.jpeg";
    import todolist from "$lib/images/todolist.jpeg";
    import smilely from "$lib/images/smiley.png";
    import somO from "$lib/images/somO.png";
    import register_late from "$lib/images/register_late.png";
    import purrfect from "$lib/images/purrfect.png";
    import golden_poo from "$lib/images/golden_poo.png";
    import catguins from "$lib/images/catguins.png";
</script>

<article id="projects" class="prose lg:mt-8 scroll-mt-20">
    <h1>Projects</h1>
</article>

<ul class="menu menu-horizontal p-8 lg:p-16 grid grid-cols-1 gap-1 lg:grid-cols-2 lg:gap-8">
    <Card src={pthipth} title="pthipth" detail="Thread Library" tags={["Final Year Project", "C","Library", "Thread"]} status={[{title: "Library", color:"badge-secondary"}]} link_github="https://github.com/kokejohh/pthipth"/>
    <Card src={koke_theme} title="Koke Theme" detail="Theme on vscode" tags={["vscode", "Theme", "Extension"]} status={[{title: "Extension", color: "badge-secondary"}]} link_github="https://github.com/kokejohh/koke-theme" link_web="https://marketplace.visualstudio.com/items?itemName=Koke.koke-theme"/>
    <!-- <Card title="บริการลบคนออกจากฝัน" detail="หากท่านมัญหากวนใจมีใครรบกวนในความฝัน" tags={["Svelte", "DaisyUI"]} status={[{title: "Web", color: "badge-primary"}]} link_github="https://github.com/kokejohh/bingbing" link_web="https://bingbing-sigma.vercel.app/"/> -->
    <Card src={portfolio} title="portfolio" detail="Website portfolio" tags={["Svelte", "TypeScript", "DaisyUI"]} status={[{title: "Website", color: "badge-primary"}]} link_github="https://github.com/kokejohh/portfolio"/>
    <Card src={valentines_day} title="valentine-day" detail="" tags={["JavaScript", "HTML", "CSS"]} status={[{title: "Website", color: "badge-primary"}]} link_github="https://github.com/kokejohh/valentine-day" link_web="https://kokejohh.github.io/valentine-day/"/>
    <Card src={loveme} title="loveme" detail="" tags={["Javascript", "HTML", "CSS"]} status={[{title: "Website", color: "badge-primary"}]} link_github="https://github.com/kokejohh/loveme" link_web="https://kokejohh.github.io/loveme/"/>
    <Card src={hostpital} title="วิเคราะห์รีวิว รพ. จาก google review ด้วย wordcloud" detail="" tags={["python", "wordcloud"]} status={[{title: "Website", color: "badge-primary"}]} link_github="https://github.com/kokejohh/loveme" link_web="https://kokejohh.github.io/loveme/"/>
    <Card src={pichit300} title="pichit300" detail="" tags={["Javascript", "HTML", "CSS"]} status={[{title: "Website", color: "badge-primary"}]} link_github="https://github.com/kokejohh/pichit300" link_web="https://kokejohh.github.io/pichit300/src/"/>
    <Card src={rush_discovery} title="rush discovery piscine 42" detail="" tags={["Javascript", "HTML", "CSS", "JSON"]} status={[{title: "Website", color: "badge-primary"}]} link_github="https://github.com/kokejohh/rush_discovery42" link_web="https://kokejohh.github.io/rush_discovery42/"/>
    <Card src={rov_supernova} title="rov supernova" detail="" tags={["Svelte", "JavaScript", "TailwindCSS"]} status={[{title: "Website", color: "badge-primary"}]} link_github="https://github.com/kokejohh/rov_supernova" link_web="https://kokejohh.github.io/rov_supernova/src/main.html"/>
    <Card src={todolist} title="todolist" detail="" tags={["JavaScript", "HTML", "CSS"]} status={[{title: "Website", color: "badge-primary"}]} link_github="https://github.com/kokejohh/project_todolist" link_web="https://kokejohh.github.io/project_todolist/"/>
    <Card src={smilely} title="smilely" detail="" tags={["Javascript", "Tree.js"]} status={[{title: "Website", color: "badge-primary"}, {title: "Game", color: "badge-warning"}]} link_web="https://www.youtube.com/watch?v=j5tPJa9jiog"/>
    <Card src={somO} title="AI chat bot somO" detail="" tags={["python", "PyThaiNLP"]} status={[{title: "Website", color: "badge-primary"}]} link_web="https://drive.google.com/drive/u/0/folders/13UO3sU6HZjyoBYw-MGMtqxIF7y9Ih8RW"/>
    <Card src={register_late} title="ลงทะเบียนล่าช้า มธ." detail="" tags={["Node.js", "Express.js", "HTML", "Bootstrap"]} status={[{title: "Website", color: "badge-primary"}]} link_web="https://sites.google.com/view/cs264-100001-group3/"/>
    <Card src={purrfect} title="Purrfect" detail="" tags={["PHP", "HTML", "CSS", "Bootsrap", "TailwindCSS", "MySQL"]} status={[{title: "Website", color: "badge-primary"}]} link_web="https://drive.google.com/drive/folders/1s87rwS5gMoW8Q2u63oAa9awv7B-kMVAE"/>
    <Card src={golden_poo} title="Gloden pool" detail="" tags={["Unity", "C#"]} status={[{title: "Game", color: "badge-warning"}]} link_web="https://www.youtube.com/watch?v=O8_jTC1FPo4"/>
    <Card src={catguins} title="Catguins 2D" detail="" tags={["Unity", "C#"]} status={[{title: "Game", color: "badge-warning"}]} link_web="https://gamejolt.com/games/catguins2d/203049"/>
</ul>