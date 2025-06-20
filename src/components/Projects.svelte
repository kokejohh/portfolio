<script>
    import Card from "./Card.svelte";

    import pthipth from "$lib/images/pthipth.jpeg";
    import todo_list_nuxt from "$lib/images/todo-list-nuxt.jpeg";
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

<ul class="menu menu-horizontal p-8 lg:p-16 grid grid-cols-1 gap-1 lg:grid-cols-2 2xl:grid-cols-3 lg:gap-8">
    <Card src={pthipth} title="pthipth" detail="Thread Library, non-preemptive priority thread library inspired by pthreads.
        non-preemptive, meaning threads voluntarily yield control. support thread priorities. each thread can have a time quota.
        each thread has its own aging mechanism to prevent starvation. can use thread pool to manage thread creation and reuse efficiently."
        tags={["Final Year Project", "C","Library", "Thread"]} status={[{title: "Library", color:"badge-secondary"}]} link_github="https://github.com/kokejohh/pthipth"/>
    <Card src={todo_list_nuxt} title="todo-list-nuxt" detail="todo-list-nuxt is a todo list website with a database using Vercel, Prisma, and PostgreSQL. It supports drag-and-drop for tasks and allows users to manage their tasks freely." tags={["Nuxt", "TypeScript", "DaisyUI", "Prisma", "SweetAlert2"]} status={[{title: "Website", color: "badge-primary"}]} link_github="https://github.com/kokejohh/todo-list-nuxt" link_web="https://todo-list-nuxt-eight.vercel.app/"/>
    <Card src={koke_theme} title="Koke Theme" detail="This VSCode theme features a dark green tone that evokes the feeling of a forest. 'Koke' is my nickname. This project uses Yeoman for scaffolding." tags={["vscode", "Theme", "Extension"]} status={[{title: "Extension", color: "badge-secondary"}]} link_github="https://github.com/kokejohh/koke-theme" link_web="https://marketplace.visualstudio.com/items?itemName=Koke.koke-theme"/>
    <!-- <Card title="บริการลบคนออกจากฝัน" detail="หากท่านมัญหากวนใจมีใครรบกวนในความฝัน" tags={["Svelte", "DaisyUI"]} status={[{title: "Web", color: "badge-primary"}]} link_github="https://github.com/kokejohh/bingbing" link_web="https://bingbing-sigma.vercel.app/"/> -->
    <Card src={portfolio} title="portfolio" detail="A personal portfolio website that showcases my past projects, professional experience, and a range of skills." tags={["Svelte", "TypeScript", "DaisyUI"]} status={[{title: "Website", color: "badge-primary"}]} link_github="https://github.com/kokejohh/portfolio"/>
    <Card src={valentines_day} title="valentine-day" detail="A simple website for writing and sending messages to someone you like on Valentine's Day. It doesn't have a backend, messages are passed using query parameters." tags={["JavaScript", "HTML", "CSS"]} status={[{title: "Website", color: "badge-primary"}]} link_github="https://github.com/kokejohh/valentine-day" link_web="https://kokejohh.github.io/valentine-day/"/>
    <Card src={loveme} title="loveme" detail="A simple website for asking your crush to be your boyfriend or girlfriend, guaranteed to work! Don't believe me? Try it yourself!" tags={["Javascript", "HTML", "CSS"]} status={[{title: "Website", color: "badge-primary"}]} link_github="https://github.com/kokejohh/loveme" link_web="https://kokejohh.github.io/loveme/"/>
    <Card src={hostpital} title="วิเคราะห์รีวิว รพ. จาก google review ด้วย wordcloud" detail="As part of the CS385 course, this project analyzes Google reviews from six hospitals to uncover common problems and feedback. A word cloud is used to highlight the most frequently mentioned terms in the reviews." tags={["python", "wordcloud"]} link_web="https://colab.research.google.com/drive/1tCniMnLSnEqUgwfHkHyZbaq4xTLRhW3e"/>
    <Card src={pichit300} title="pichit300" detail="This project is designed to be a web-based platform for practicing coding problems. At this stage, only the front-end has been developed." tags={["Javascript", "HTML", "CSS", "JSON"]} status={[{title: "Website", color: "badge-primary"}]} link_github="https://github.com/kokejohh/pichit300" link_web="https://pichit300.vercel.app"/>
    <Card src={rush_discovery} title="rush discovery piscine 42" detail="A simple portfolio website created as part of my participation in the Discovery Piscine 42 program by 42 Bangkok." tags={["Javascript", "HTML", "CSS"]} status={[{title: "Website", color: "badge-primary"}]} link_github="https://github.com/kokejohh/rush_discovery42" link_web="https://kokejohh.github.io/rush_discovery42/"/>
    <Card src={rov_supernova} title="rov supernova" detail="A website for selecting and banning characters in RoV. Currently, only the front-end has been developed." tags={["Svelte", "JavaScript", "TailwindCSS"]} status={[{title: "Website", color: "badge-primary"}]} link_github="https://github.com/kokejohh/rov_supernova" link_web="https://kokejohh.github.io/rov_supernova/src/main.html"/>
    <Card src={todolist} title="todolist" detail="This website was created as part of an internship test for BorntoDev. It's a simple to-do list app that allows users to add, edit, and delete tasks, with data stored in localStorage." tags={["JavaScript", "HTML", "CSS"]} status={[{title: "Website", color: "badge-primary"}]} link_github="https://github.com/kokejohh/project_todolist" link_web="https://kokejohh.github.io/project_todolist/"/>
    <Card src={smilely} title="smilely" detail="This project is part of the CS299 course and involves 3D graphics using Three.js to render 3D content on the web. The project is a simple, cute game featuring a bright smiling character." tags={["Javascript", "Three.js"]} status={[{title: "Game", color: "badge-warning"}, {title: "Website", color: "badge-primary"}]} link_web="https://www.youtube.com/watch?v=j5tPJa9jiog"/>
    <Card src={somO} title="AI chat bot somO" detail="This project is part of the CS265 course and involves building a simple chatbot using the ChatterBot library. It implements the Jaccard Similarity algorithm and utilizes pythaiNLP for Thai language processing, including normalization, word tokenization, stopwords removal, and part-of-speech tagging." tags={["python", "PyThaiNLP"]} link_web="https://drive.google.com/drive/u/0/folders/13UO3sU6HZjyoBYw-MGMtqxIF7y9Ih8RW"/>
    <Card src={register_late} title="ลงทะเบียนล่าช้า มธ." detail="This project is part of the CS264 course and involves developing a web application for late course registration at Thammasat University. The system includes features for both students and instructors." tags={["Node.js", "Express.js", "HTML", "Bootstrap"]} status={[{title: "Website", color: "badge-primary"}]} link_web="https://sites.google.com/view/cs264-100001-group3/"/>
    <Card src={purrfect} title="Purrfect" detail="This project is part of the CS251 course and involves database development. The project is a web application called 'Purrfect,' inspired by the sound of a cat. It’s a cat café website where customers can adopt cats if they are interested." tags={["PHP", "HTML", "CSS", "Bootsrap", "TailwindCSS", "MySQL"]} status={[{title: "Website", color: "badge-primary"}]} link_web="https://drive.google.com/drive/folders/1s87rwS5gMoW8Q2u63oAa9awv7B-kMVAE"/>
    <Card src={golden_poo} title="Gloden poo" detail="It’s a game about a Kra-Sue (a Thai ghost) eating something dirty, haha! You can probably guess from the game’s name." tags={["Unity", "C#"]} status={[{title: "Game", color: "badge-warning"}, {title: "Android", color: "badge-secondary"}]} link_web="https://www.youtube.com/watch?v=O8_jTC1FPo4"/>
    <Card src={catguins} title="Catguins 2D" detail="This game is inspired by Flappy Bird, but mine features a character that's a mix of a cat and a penguin. Of course, it loves eating fish!" tags={["Unity", "C#"]} status={[{title: "Game", color: "badge-warning"}, {title: "Windows", color: "badge-secondary"}]} link_web="https://gamejolt.com/games/catguins2d/203049"/>
</ul>