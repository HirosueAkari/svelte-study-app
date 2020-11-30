<script lang="ts">
  import Router from 'svelte-spa-router'
  import Home from './components/pages/Home.svelte'
  import Login from './components/pages/Login.svelte'

  const routes: any = {
    '/': Home,
    '/login': Login
  }
</script>

<body>
  <Router {routes}/>
</body>
