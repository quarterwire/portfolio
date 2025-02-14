<script>
  import Page from "../routes/+page.svelte";

</script> 

<main class="flex flex-col flex-1 p-4">
	<section id="introPage" class="grid grid-cols-1 gap-3 py-8 sm:py-14">
		<div class="flex items-center justify-center gap-3">
			<img src="https://i.pinimg.com/736x/44/1d/af/441daf69b2197c0b19219babf8e9a0db.jpg" alt="profile-picture" class="rounded-full w-15"/>
			<h2 class="py-3 px-5 border border-[#4d4d4d] rounded-4xl text-2xl">Hello, I'm Ionut</h2>
		</div>
		<div class="text-white flex text-[10px] items-center justify-center gap-2 pr-6 sm:ml-10">
				<h1 class="text-5xl font-semibold text-accentv md:text-6xl lg:text-8xl">SOFTWARE</h1>
				<p class="sm:text-xs md:text-sm lg:text-base text-center"> // Based in <br/> Brasov, Romania</p>
		</div>
		<div class="text-white flex text-[10px] items-center justify-center gap-4">
			<h1 class="text-5xl font-semibold text-accenty md:text-6xl lg:text-8xl">
				DEVELOPER
			</h1>
		</div>
		<div class="text-white flex text-[10px] items-center justify-center gap-4">
			<h1 class="text-5xl font-semibold text-accenty md:text-6xl lg:text-8xl">
				& DESIGNER
			</h1>
			<button class="p-3 border border-[#4d4d4d] rounded-3xl text-base flex gap-3 items-center"><i class="fa-solid fa-circle-plus  text-green-300"></i>// Let's Connect </button>
		</div>
		<div class="flex items-center justify-center">
			<p class="text-3xl font-medium py-5 text-center	">I design a digital experience that veers toward <br/> <span class="text-cyan-400">usefulness</span>, <span class="text-yellow-400">efficency</span>, and <span class="text-violet-400">beauty</span>.</p>

		</div>
	</section>
</main>
