<main>
  <div class="card">
    <h1>Svelte Study App</h1>
    <div>
      <input type="text" class="input" placeholder="E-mail">
      <input type="password" class="input" placeholder="Password">
      <Button btnLabel={"LOGIN"} on:clickBtn={clickBtn} />
    </div>
  </div>
</main>
<script lang="ts">
import { push } from 'svelte-spa-router'
import Button from '../atoms/Button.svelte'

function clickBtn () {
  push('/home')
}
</script>
<style lang="scss">
.input {
  display: block;
  width: 300px;
  margin: 16px auto;
}
.card {
  width: 500px;
  border-radius: 2px;
  box-shadow: 0px 3px 1px -2px rgba(0,0,0,0.2),
    0px 2px 2px 0px rgba(0,0,0,0.14),
    0px 1px 5px 0px rgba(0,0,0,0.12);
  text-align: center;
}
h1 {
  padding: 16px;
}
</style>
