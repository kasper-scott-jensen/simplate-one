<script>
    import { Router, Route } from 'svelte-navigator'

    import Index from './pages/Index.svelte'
</script>

<Router primary={false}>
    <Route path={'/'} component={Index} />
</Router>
