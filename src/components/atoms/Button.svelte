<button on:click={clickBtn}>{btnLabel}</button>

<script lang="ts">
export let btnLabel: string

function clickBtn() {
  alert('ボタンクリック')
}
</script>
<style lang="scss">
button {
  border-radius: 2px;
  box-shadow: 0px 3px 1px -2px rgba(0,0,0,0.2),
    0px 2px 2px 0px rgba(0,0,0,0.14),
    0px 1px 5px 0px rgba(0,0,0,0.12);
  color: white;
  background-color: #1867c0;
  border-color: #1867c0;
  padding: 0 16px;
  height: 36px;
}
</style>
