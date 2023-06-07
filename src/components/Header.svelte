<script lang="ts">
    import { goto } from "$app/navigation";
    import miLogo from "../assets/Logo-negro.png"

    function backToIndex() {
        goto(`/`)
    }
</script>

<style>
    .Header .Header-top-section{
        display: flex;
        justify-content: flex-end;
        align-items: center;
        background-color: #48CFAD;
        height: 60px;
    }
    
    .Header .Header-top-section .Header-social-networks {
        margin-right: 10px;
    }

    .Header .Header-top-section .Header-social-networks svg{
        margin-left: 20px;
    }

    .Header .Header-bottom-section{
        background-color: #F3EFF5;
    }

    .Header .Header-bottom-section img{
        width: 200px;
    }
    
    .Header .Header-bottom-section .Header-container {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .Header .Header-bottom-section .Header-container .Header-about-section {
        margin-right: 10px;
    }

    .Header .Header-bottom-section .Header-container .Header-about-section a {
        color: #0B0A07;
        margin-top: 20px;

        font-family: monospace;
        font-size: 15px;
        font-weight: 700;
    }
</style>

<!-- markup (zero or more items) goes here -->

<div class="Header">
    <div class="Header-top-section">
        <div class="Header-social-networks">
            
            <a href="#">
                <svg xmlns="http://www.w3.org/2000/svg" color="#F3EFF5" class="icon icon-tabler icon-tabler-brand-facebook" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                    <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                    <path d="M7 10v4h3v7h4v-7h3l1 -4h-4v-2a1 1 0 0 1 1 -1h3v-4h-3a5 5 0 0 0 -5 5v2h-3"></path>
                </svg>
            </a>

            <a href="#">
                <svg xmlns="http://www.w3.org/2000/svg" color="#F3EFF5" class="icon icon-tabler icon-tabler-brand-twitter" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                    <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                    <path d="M22 4.01c-1 .49 -1.98 .689 -3 .99c-1.121 -1.265 -2.783 -1.335 -4.38 -.737s-2.643 2.06 -2.62 3.737v1c-3.245 .083 -6.135 -1.395 -8 -4c0 0 -4.182 7.433 4 11c-1.872 1.247 -3.739 2.088 -6 2c3.308 1.803 6.913 2.423 10.034 1.517c3.58 -1.04 6.522 -3.723 7.651 -7.742a13.84 13.84 0 0 0 .497 -3.753c0 -.249 1.51 -2.772 1.818 -4.013z"></path>
                </svg>
            </a>
            
            <a href="#">

                <svg xmlns="http://www.w3.org/2000/svg" color="#F3EFF5" class="icon icon-tabler icon-tabler-brand-instagram" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                    <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                    <path d="M4 4m0 4a4 4 0 0 1 4 -4h8a4 4 0 0 1 4 4v8a4 4 0 0 1 -4 4h-8a4 4 0 0 1 -4 -4z"></path>
                    <path d="M12 12m-3 0a3 3 0 1 0 6 0a3 3 0 1 0 -6 0"></path>
                    <path d="M16.5 7.5l0 .01"></path>
                </svg>

            </a>
            
            <a href="#">

                <svg xmlns="http://www.w3.org/2000/svg" color="#F3EFF5" class="icon icon-tabler icon-tabler-brand-linkedin" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                    <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                    <path d="M4 4m0 2a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-12a2 2 0 0 1 -2 -2z"></path>
                    <path d="M8 11l0 5"></path>
                    <path d="M8 8l0 .01"></path>
                    <path d="M12 16l0 -5"></path>
                    <path d="M16 16v-3a2 2 0 0 0 -4 0"></path>
                </svg>

            </a>
            
            <a href="#">

                <svg xmlns="http://www.w3.org/2000/svg" color="#F3EFF5" class="icon icon-tabler icon-tabler-brand-youtube" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                    <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                    <path d="M3 5m0 4a4 4 0 0 1 4 -4h10a4 4 0 0 1 4 4v6a4 4 0 0 1 -4 4h-10a4 4 0 0 1 -4 -4z"></path>
                    <path d="M10 9l5 3l-5 3z"></path>
                </svg>

            </a>
        </div>
    </div>
    <div class="Header-bottom-section">
        <div class="Header-container">
            <div class="Header-logo-section">
                <img on:click={backToIndex} src="{miLogo}" alt="">
            </div>
            <div class="Header-about-section">
                <a href="/profile">About me</a>
            </div>
        </div>
    </div>
</div>