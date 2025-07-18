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

    h1 {
        font-size: 3.2em;
        margin-bottom: 1em;
        letter-spacing: 2px; /* Adds to the sleek look */
        font-family: "Lato", "Helvetica Neue", Arial, sans-serif;
        line-height: 1.6;
        max-width: 800px;
        margin: 0; /* Remove auto centering */
        padding: 50px 20px 20px 40px; /* Remove left padding to truly hug left */
        font-style: italic;
        font-weight: 200;
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
    }
</style>

