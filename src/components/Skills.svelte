<script>
    import SkillHover from './Skill_hover.svelte';
</script>

<article class="prose prose-p:font-black prose-p:text-xl  lg:w-screen mb-32">
    <h1>Skills</h1>
    
    <div class="flex flex-col">
        <p>Programming Language</p>
        <div class="flex flex-row space-x-2">
        <SkillHover icon_class="devicon-plain:c" text="c"/>
        <SkillHover icon_class="devicon-plain:cplusplus" text="C++" />
        <SkillHover icon_class="devicon-plain:java" text="Java" />
        <SkillHover icon_class="devicon-plain:python" text="Python" />
        <SkillHover icon_class="file-icons:go" text="Go" />
        <SkillHover icon_class="devicon-plain:rust" text="Rust" />
        </div>
    </div>
     <div class="flex flex-col">
        <p>Front-end development</p>
        <div class="flex flex-row space-x-2">
            <SkillHover icon_class="devicon-plain:html5" text="HTML5" />
            <SkillHover icon_class="devicon-plain:css3" text="CSS3" />
            <SkillHover icon_class="devicon-plain:javascript" text="JavaScript" />
            <SkillHover icon_class="devicon-plain:typescript" text="TypeScript" />
            <SkillHover icon_class="devicon-plain:svelte" text="Svelte" />
            <SkillHover icon_class="file-icons:tailwind" text="TailwindCSS" />
        </div>
     </div>
     <div class="flex flex-col">
        <p>Back-end development</p>
        <div class="flex flex-row space-x-2">
            <SkillHover icon_class="devicon-plain:nodejs" text="Node.js" />
            <SkillHover icon_class="file-icons:sequelize" text="Sequelize" />
            <SkillHover icon_class="devicon-plain:mysql-wordmark" text="MySQL" />
            <SkillHover icon_class="devicon-plain:php" text="PHP" />
        </div>
    </div>
     <div class="flex flex-col">
        <p>Game Development</p>
        <div class="flex flex-row space-x-2">
            <SkillHover icon_class="devicon-plain:csharp" text="C#" />
            <SkillHover icon_class="devicon-plain:unity" text="Unity" />
            <SkillHover icon_class="file-icons:blender" text="Blender" />
        </div>
     </div>
     <div class="flex flex-col">
        <p>Tools</p>
        <div class="flex flex-row space-x-2">
            <SkillHover icon_class="devicon-plain:linux" text="Linux" />
            <SkillHover icon_class="devicon-plain:neovim" text="Neovim" />
            <SkillHover icon_class="devicon-plain:git" text="Git" />
            <SkillHover icon_class="devicon-plain:postman" text="Postman" />
            <SkillHover icon_class="file-icons:figma" text="Figma" />
        </div>
     </div>

</article>