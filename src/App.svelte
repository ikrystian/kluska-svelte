<script lang="ts">
  import { Router, Route } from 'svelte-routing';
  import Welcome from './views/Welcome.svelte';
  import Auth from './views/auth/Auth.svelte';
  export let url ='';
</script>
<Router {url}>
    <Route path="/"><Welcome /></Route>
    <Route path="/auth/*" component={Auth} />
</Router>
