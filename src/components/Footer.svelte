<script>
     let year = new Date().getFullYear();

     let socialMedia = [
        {
            name: "Github",
            icon: "ri-github-fill",
            link: "https://github.com/unoxdevs"
        },
        {
            name: "Linkedin",
            icon: "ri-linkedin-fill",
            link: "https://linkedin.com/company/unoxdevs"
        },
        {
            name: "Instagram",
            icon: "ri-instagram-fill",
            link: "https://instagram.com/unoxdevs"
        },
        {
            name: "Twitter",
            icon: "ri-twitter-fill",
            link: "https://twitter.com/unoxdevs"
        }
     ]
</script>

<div class="text-center text-white/20 bottom-0 fixed mx-5">
    <p class="text-xs my-5 font-thin">© {year} UnoxDevs. All rights reserved.</p>
    <div class="flex">
        {#each socialMedia as social}
            <a href={social.link} target="_blank" rel="noopener noreferrer" class="hover:text-white/100 transition-all duration-300 my-5 -mt-[0.5rem] mx-1 bg-[#141414] px-1.5 rounded-full">
                <i class="{social.icon} relative top-[1px]"></i>
            </a>
        {/each}
    </div>
</div>