<script>
    import Exp from "./Exp.svelte";
    import Footer from "./Footer.svelte";
    import Home from "./Home.svelte";
    import Projects from "./Projects.svelte";
    import Skill from "./Skills.svelte";
    import Icon from "@iconify/svelte";

    import { TypeWriter } from "svelte-typewrite";
</script>

<div class="navbar bg-base-100 px-8 fixed z-1">
    <div class="navbar-start">
        <div class="dropdown">
            <label
                for="my-drawer-2"
                aria-label="open sidebar"
                class="btn btn-square btn-ghost lg:hidden"
            >
                <svg
                    xmlns="http://www.w3.org/2000/svg"
                    class="h-5 w-5"
                    fill="none"
                    viewBox="0 0 24 24"
                    stroke="currentColor"
                >
                    <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M4 6h16M4 12h8m-8 6h16"
                    />
                </svg>
            </label>
        </div>
    </div>
    <div class="navbar-center">
        <ul class="menu menu-horizontal">
            <li class="text-2xl font-black">Pitchakorn Thiprangsi</li>
        </ul>
    </div>
    <div class="navbar-end">
        <label class="swap swap-rotate">
            <input type="checkbox" class="theme-controller" value="dim" />

            <svg
                class="swap-off h-8 w-8 fill-current"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 24 24"
            >
                <path
                    d="M5.64,17l-.71.71a1,1,0,0,0,0,1.41,1,1,0,0,0,1.41,0l.71-.71A1,1,0,0,0,5.64,17ZM5,12a1,1,0,0,0-1-1H3a1,1,0,0,0,0,2H4A1,1,0,0,0,5,12Zm7-7a1,1,0,0,0,1-1V3a1,1,0,0,0-2,0V4A1,1,0,0,0,12,5ZM5.64,7.05a1,1,0,0,0,.7.29,1,1,0,0,0,.71-.29,1,1,0,0,0,0-1.41l-.71-.71A1,1,0,0,0,4.93,6.34Zm12,.29a1,1,0,0,0,.7-.29l.71-.71a1,1,0,1,0-1.41-1.41L17,5.64a1,1,0,0,0,0,1.41A1,1,0,0,0,17.66,7.34ZM21,11H20a1,1,0,0,0,0,2h1a1,1,0,0,0,0-2Zm-9,8a1,1,0,0,0-1,1v1a1,1,0,0,0,2,0V20A1,1,0,0,0,12,19ZM18.36,17A1,1,0,0,0,17,18.36l.71.71a1,1,0,0,0,1.41,0,1,1,0,0,0,0-1.41ZM12,6.5A5.5,5.5,0,1,0,17.5,12,5.51,5.51,0,0,0,12,6.5Zm0,9A3.5,3.5,0,1,1,15.5,12,3.5,3.5,0,0,1,12,15.5Z"
                />
            </svg>

            <svg
                class="swap-on h-8 w-8 fill-current"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 24 24"
            >
                <path
                    d="M21.64,13a1,1,0,0,0-1.05-.14,8.05,8.05,0,0,1-3.37.73A8.15,8.15,0,0,1,9.08,5.49a8.59,8.59,0,0,1,.25-2A1,1,0,0,0,8,2.36,10.14,10.14,0,1,0,22,14.05,1,1,0,0,0,21.64,13Zm-9.5,6.69A8.14,8.14,0,0,1,7.08,5.22v.27A10.15,10.15,0,0,0,17.22,15.63a9.79,9.79,0,0,0,2.1-.22A8.11,8.11,0,0,1,12.14,19.73Z"
                />
            </svg>
        </label>
    </div>
</div>

<div class="drawer lg:drawer-open bg-base-100">
    <input id="my-drawer-2" type="checkbox" class="drawer-toggle" />
    <div class="drawer-content flex flex-col items-center justify-center">
        <Home />
        <Skill />
        <Exp />
        <Projects />
        <Footer />
    </div>
    <div class="drawer-side">
        <label
            for="my-drawer-2"
            aria-label="close sidebar"
            class="drawer-overlay"
        ></label>
        <ul
            class="menu bg-base-100 text-base-content min-h-full w-64 lg:w-80 pt-16 py-8 justify-between"
        >
            <div>
                <div class="font-black text-md lg:text-xl mb-4">
                    <TypeWriter
                        texts={[
                            "Looking for a developer ?",
                            "Your next developer is here.",
                        ]}
                    />
                </div>
                <li>
                    <a href="#home" on:click={() => { document.getElementById("my-drawer-2")?.click(); }} class="p2 lg:p-4 hover:font-medium  active:font-black text-lg lg:text-xl"
                        >Home</a
                    >
                </li>
                <li>
                    <a href="#skills" on:click={() => { document.getElementById("my-drawer-2")?.click(); }} class="p2 lg:p-4 hover:font-medium text-lg lg:text-xl"
                        >Skills</a
                    >
                </li>
                <li>
                    <a href="#experience" on:click={() => { document.getElementById("my-drawer-2")?.click(); }} class="p2 lg:p-4 hover:font-medium text-lg lg:text-xl"
                        >Experience</a
                    >
                </li>
                <li>
                    <a href="#projects" on:click={() => { document.getElementById("my-drawer-2")?.click(); }} class="p2 lg:p-4 hover:font-medium text-lg lg:text-xl"
                        >Projects</a
                    >
                </li>
            </div>
            <div class="space-y-8">
                <div class="mockup-code w-full">
                    <pre data-prefix="$" class="text-xs lg:text-base"><code
                            >cat info</code
                        ></pre>
                    <pre
                        data-prefix=">"
                        class="text-success text-xs lg:text-base"><code
                            >pithcakorn.thip@gmail.com</code
                        ></pre>
                    <pre
                        data-prefix=">"
                        class="text-success text-xs lg:text-base"><code
                            >+66858189451</code
                        ></pre>
                </div>
                <li class="flex flex-row justify-center">
                    <a href="https://github.com/kokejohh/" target="_blank">
                        <Icon
                            icon="octicon:mark-github-16"
                            width="32"
                            height="32"
                        />
                    </a>
                    <a href="https://th.linkedin.com/in/pitchakorn-thiprangsi-a282a129a" target="_blank">
                        <Icon
                            icon="devicon-plain:linkedin"
                            width="32"
                            height="32"
                        />
                    </a>
                    <a href="https://www.instagram.com/pitchakornkoke/" target="_blank">
                        <Icon
                            icon="entypo-social:instagram"
                            width="32"
                            height="32"
                        />
                    </a>
                    <a href="https://web.facebook.com/Pitchakorn.Koke" target="_blank">
                        <Icon
                            icon="entypo-social:facebook"
                            width="32"
                            height="32"
                        />
                    </a>
                </li>
            </div>
        </ul>
    </div>
</div>
