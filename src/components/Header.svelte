<script>
    let tabs = [{
        name: "Home",
        link: "#", 
        icon: "house"
        
    },
    {
        name: "Projects",
        link: "/projects", 
        icon: "suitcase"
    },
    {
        name: "About me",
        link: "/about-me", 
        icon: "id-card"
    }]
</script>

<header class="px-6 flex items-center justify-between border-b border-[#4d4d4d] py-6 bg-transparent "> 
    <h1 class="font-bold flex gap-3 items-center justify-center text-2xl border border-[#4d4d4d] rounded-3xl p-2"><span class="rounded-full w-5 h-5 bg-white"></span> Ionut S.</h1>
    <div class="flex items-center justify-center gap-6 border-[#4d4d4d] p-3 border rounded-3xl">
        {#each tabs as tab, index}
        <a href={tab.link} class="hover:text-[#D84040] duration-200 gap-3 flex items-center">
            <i class="fa-solid fa-{tab.icon}"></i>
            <p>{tab.name}</p>
        </a>
        {/each}
    </div>
    <button class="hover:text-[#D84040] duration-200 p-3 flex items-center gap-3 justify-center font-medium rounded-3xl border border-[#4d4d4d]">
        Contact me
        <i class="fa-solid fa-paper-plane"></i>

    </button>
</header>