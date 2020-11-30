<main>
  <h1>Home</h1>
  <button on:click={clickLogin}>Login</button>
</main>

<script lang="ts">
import { push } from "svelte-spa-router"

const clickLogin = () => {
  push('/login')
}
</script>
