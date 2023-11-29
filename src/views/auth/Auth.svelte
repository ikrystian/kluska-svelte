<script lang="ts">
    import { Router, Route } from 'svelte-routing';
    import Login from './Login.svelte';
    import Register from './Register.svelte';
    export let url ='/auth';
</script>
<Router {url}>
    <Route path="/login" component={Login}></Route>
    <Route path="/register" component={Register}></Route>
</Router>
