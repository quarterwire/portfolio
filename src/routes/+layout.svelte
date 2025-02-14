<script>
    import Footer from "../components/Footer.svelte";
    import Header from "../components/Header.svelte";
    import "../app.css";
	import '@fortawesome/fontawesome-free/css/all.min.css'
  import Main from "../components/Main.svelte";
</script>

<div
    class="container relative flex flex-col max-w-[1400px] mx-auto w-full text-sm sm:text-base min-h-screen"
>
    <Header/>
	<Main/>
    <Footer />
</div>