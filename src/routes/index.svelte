<main class="bg-red-400">
  <button class="btn btn-primary">primary</button>
  <button class="btn btn-secondary">secondary</button>
</main>

<style global>
  .btn{
    border: 2px yellow solid;
    padding: 1em;
  }
  .btn:where(.btn-primary,.btn-secondary){
    background-color: green;
  }
</style>