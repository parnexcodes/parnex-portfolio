<script>
    import Footer from "../components/Footer.svelte";
    import Socials from "../components/Socials.svelte";
    import Header from "../components/Header.svelte";
</script>

<svelte:head>
    <title>parnex - home</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Exo:wght@800&family=Maven+Pro:wght@900&display=swap');
    </style> 
</svelte:head>

<div class="bg-neutral-900 h-screen overflow-hidden">
    <Header />
    <div class="flex flex-col justify-center items-center h-full pb-32">
        <div class="font-exo tracking-wider text-8xl bg-gradient-to-r from-[#007CF0] to-[#00DFD8] text-transparent bg-clip-text">
            parnex
        </div>
        <div class="text-md pt-4 text-gray-200">
            Developer | Gamer | Cinephile | Technophile
        </div>
        <Socials />
        <Footer />
    </div>
</div>