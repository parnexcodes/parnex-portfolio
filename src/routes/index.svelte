<script>
    import Footer from "../components/Footer.svelte";
    import Socials from "../components/Socials.svelte";
</script>

<svelte:head>
    <title>parnex - portfolio website</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Exo:wght@800&family=Maven+Pro:wght@900&display=swap');
    </style> 
</svelte:head>

<div class="bg-neutral-900 h-screen">
    <div class="flex flex-col justify-center items-center h-screen">
        <div class="font-exo tracking-wider text-8xl bg-gradient-to-r from-[#007CF0] to-[#00DFD8] text-transparent bg-clip-text">
            parnex
        </div>
        <div class="text-md pt-4 text-gray-200">
            ReactJS | Svelte | React Native | AWS
        </div>
        <Footer />
        <Socials />
    </div>
</div>