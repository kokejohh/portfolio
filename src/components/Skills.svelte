<script>
    import SkillBox from './Skill_Box.svelte';
    import SkillHover from './Skill_hover.svelte';
</script>

<article id="skills" class="mx-8 prose prose-p:font-black prose-p:text-xl lg:w-screen mb-32 lg:grid lg:grid-cols-6 scroll-mt-20">
    <h1 class="lg:col-start-3 lg:col-end-6">Skills</h1>
    <SkillBox title="Programming Language" position="left">
        <div class="flex flex-row space-x-2">
            <SkillHover icon_class="devicon-plain:c" text="C"/>
            <SkillHover icon_class="devicon-plain:cplusplus" text="C++" />
            <SkillHover icon_class="devicon-plain:python" text="Python" />
            <SkillHover icon_class="devicon-plain:java" text="Java" />
            <SkillHover icon_class="file-icons:go" text="Go" />
        </div>
    </SkillBox>

    <SkillBox title="Front-end development" position="right">
        <SkillHover icon_class="devicon-plain:html5" text="HTML5" />
        <SkillHover icon_class="devicon-plain:css3" text="CSS3" />
        <SkillHover icon_class="devicon-plain:javascript" text="JavaScript" />
        <SkillHover icon_class="devicon-plain:typescript" text="TypeScript" />
        <SkillHover icon_class="file-icons:tailwind" text="TailwindCSS" />
    </SkillBox>
    
    <SkillBox title="Back-end development" position="left">
        <SkillHover icon_class="devicon-plain:nodejs" text="Node.js" />
        <SkillHover icon_class="devicon-plain:php" text="PHP" />
        <SkillHover icon_class="devicon-plain:salesforce" text="Salesforce" />
        <!-- <SkillHover icon_class="devicon-plain:spring" text="Spring Boot" /> -->
    </SkillBox>

    <SkillBox title="Fullstack Frameworks" position="right">
        <SkillHover icon_class="devicon-plain:nextjs" text="Next.js" />
        <SkillHover icon_class="devicon-plain:nuxtjs" text="Nuxt.js" />
        <SkillHover icon_class="devicon-plain:svelte" text="SvelteKit" />
    </SkillBox>

    <SkillBox title="Database" position="left">
        <div class="flex flex-row flex-wrap space-y-2 space-x-2">
            <SkillHover icon_class="file-icons:sequelize" text="Sequelize" />
            <SkillHover icon_class="file-icons:prisma" text="Prisma" />
            <SkillHover icon_class="devicon-plain:mysql-wordmark" text="MySQL" />
            <SkillHover icon_class="devicon-plain:postgresql" text="PostgreSQL" />
        </div>
    </SkillBox>

    <SkillBox title="Game development" position="right">
        <SkillHover icon_class="devicon-plain:csharp" text="C#" />
        <SkillHover icon_class="devicon-plain:unity" text="Unity" />
        <SkillHover icon_class="file-icons:blender" text="Blender" />
    </SkillBox>

    <SkillBox title="Tools" position="left">
        <SkillHover icon_class="devicon-plain:linux" text="Linux" />
        <SkillHover icon_class="devicon-plain:neovim" text="Neovim" />
        <SkillHover icon_class="devicon-plain:git" text="Git" />
    </SkillBox>
</article>