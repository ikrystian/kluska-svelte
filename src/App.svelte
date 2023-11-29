<script>
  import { Router, Route } from 'svelte-routing';
  import Welcome from './views/Welcome.svelte';
  export let url ='';
</script>
<Router {url}>
    <Route path="/"><Welcome /></Route>
</Router>
