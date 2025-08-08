<script lang="ts"> 
 import { ModeWatcher } from "mode-watcher"; 
 import Footer from '$lib/components/Footer.svelte';
</script> 

<ModeWatcher />
<h1>Public Module Development</h1> 
<hr />
<p>
</p>
<Footer />

<style>
    @import url('https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100;0,200;0,300;1,100;1,200;1,300&family=Lato:ital,wght@0,100;0,300;1,100;1,300&display=swap');

    :global(body) {
        background:  #FAF9F6; /* light background */
        min-height: 100vh;
        margin: 0;
        padding: 0;
        color: #333;
    }
    :global(body.dark) {
        background: #121212;
        color: #E0E0E0;
    }

    h1 {
        font-size: 3.2em;
        margin-bottom: 1em;
        letter-spacing: 2px;
        font-family: "Lato", "Helvetica Neue", Arial, sans-serif;
        line-height: 1.6;
        max-width: 800px;
        margin: 0;
        padding: 50px 20px 20px 40px;
        font-style: italic;
        font-weight: 200; 
        text-align: left; 
        white-space: nowrap;
        transition: color 0.2s;
    }
    :global(body.dark) h1 {
        color: #E0E0E0;
    }

    hr { 
        display: block;
        margin-top: 0.5em;
        margin-bottom: 0.5em;
        margin-left: 100px;
        margin-right: auto;
        border-style: inset;
        border-width: 1px;
        width: 70%;
        border-color: #333;
        transition: border-color 0.2s;
    }
    :global(body.dark) hr {
        border-color: #E0E0E0;
    }

    p {
        transition: color 0.2s;
    }
    :global(body.dark) p {
        color: #E0E0E0;
    }

    /* responsive adjustments made for mobile */
    @media (max-width: 600px) {
        h1 {
            font-size: 1.5em;
            padding: 30px 10px 10px 10px;
            max-width: 100vw;
            overflow-x: auto;
            font-weight: 300;
        }
        hr {
            margin-left: 0;
            width: 90%;
        }
    }
</style>

