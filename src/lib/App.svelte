<script lang="ts">
    import Nested from './Nested.svelte'; 
    import Lowercase from './Lowercase.svelte';
</script>  

<p> this is a paragraph.</p> 
<Nested />
<Lowercase />
<style> 
    /* svelte allows us to add style tags to components, just like in HTML 
       these rules are scoped to the component - won't accidentally change the style of <p> 
       elements elsewhere in your app
    */
    p {
      color: goldenrod;
      font-family: 'Comic Sans Mono';
      font-size: 2em;
    }
</style>
