<script lang="ts">
  import Router from 'svelte-spa-router'
  import Home from './components/pages/Home.svelte'

  const routes = {
    '/': Home
  };
</script>

<body>
  <Router {routes}/>
</body>
