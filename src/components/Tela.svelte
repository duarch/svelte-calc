<script lang="ts">
  export let valor: string;
</script>

<div class="tela">
  <span>{valor}</span>
</div>

<style>
  .tela {
    display: flex;
    flex: 1;
    justify-content: flex-end;
    align-items: center;
    background-color: antiquewhite;
    padding: 0px 5px;
    border-radius: 5px 5px 0px 0px;
    overflow: hidden;
    font-size: 1.7rem;
    margin: 1px;
  }
</style>
