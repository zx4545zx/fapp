<script>
  import History from "../lib/History.svelte";
</script>

<div class="card w-full bg-neutral text-neutral-content mb-3">
  <div class="card-body items-center text-center">
    <h1 class="card-title text-5xl">0</h1>
    <span>THB</span>
  </div>
</div>

<div class="w-full flex justify-center gap-3 mb-3">
  <div class="card w-full bg-neutral text-neutral-content">
    <div class="card-body items-center text-center">
      <h2 class="card-title text-xl">0</h2>
      <span>THB</span>
      <div class="card-actions justify-center">
        <button class="btn btn-success">Deposit</button>
      </div>
    </div>
  </div>
  <div class="card w-full bg-neutral text-neutral-content">
    <div class="card-body items-center text-center">
      <h2 class="card-title text-xl">0</h2>
      <span>THB</span>
      <div class="card-actions justify-center">
        <button class="btn btn-error">Withdrawal</button>
      </div>
    </div>
  </div>
</div>

<History limit={10} />
