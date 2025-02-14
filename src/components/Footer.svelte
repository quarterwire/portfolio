<script> 
    let outlets = [ {
        name: "twitter",
        icon: "twitter",
        link: "https://x.com/@thequarterwire"
    },
    {
        name: "github",
        icon: "github",
        link: "https://github.com/quarterwire"
    },
    {
        name: "linkedin",
        icon: "linkedin",
        link: "https://www.linkedin.com/in/stoica-ionut-alex-038aa42b5/"
    }]
</script>

<footer class="border-[#4d4d4d] border-t py-3 flex flex-row justify-between">
    <div class=""> 
        <p>// Design, Code,
            <br/>Engage</p> 
    </div>

    <div class="text-4xl gap-3 flex">
        {#each outlets as outlet, index}
            <a target="_blank" class="hover:text-[#D84040] duration-200 hover:scale-[1.2]" href={outlet.link}> <i class="fa-brands fa-{outlet.icon}"></i></a>
        {/each}
    </div>

    <div class="p-3 rounded-3xl border flex items-center border-[#4d4d4d] gap-3">
        <div class="w-10 h-10 bg-[#EEEEEE] rounded-full flex items-center justify-center">
          <i class="fa-regular fa-envelope text-2xl text-[#1D1616] leading-none"></i>
        </div>
        stoicaionutalex05@gmail.com
      </div>
      
</footer>