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

<div class="card w-full bg-neutral text-neutral-content mb-3">
  <div class="card-body items-center text-center">
    <h2 class="card-title text-xl">0</h2>
    <span>THB</span>
    <div class="card-actions justify-center">
      <label for="my-modal-6" class="btn btn-primary">open modal</label>
    </div>
  </div>
</div>

<History limit={10} />

<input type="checkbox" id="my-modal-6" class="modal-toggle" />
<div class="modal modal-bottom sm:modal-middle">
  <div class="modal-box">
    <h3 class="font-bold text-lg">Congratulations random Internet user!</h3>
    <p class="py-4">
      You've been selected for a chance to get one year of subscription to use
      Wikipedia for free!
    </p>

    <main class="items-center text-center m-auto">
      <div class="mockup-phone border-primary">
        <div class="camera" />
        <div class="display">
          <div class="artboard artboard-demo phone-1">Hi.</div>
        </div>
      </div>

      <div class="stats stats-vertical shadow">
        <div class="stat">
          <div class="stat-title">Downloads</div>
          <div class="stat-value">31K</div>
          <div class="stat-desc">Jan 1st - Feb 1st</div>
        </div>

        <div class="stat">
          <div class="stat-title">New Users</div>
          <div class="stat-value">4,200</div>
          <div class="stat-desc">↗︎ 400 (22%)</div>
        </div>

        <div class="stat">
          <div class="stat-title">New Registers</div>
          <div class="stat-value">1,200</div>
          <div class="stat-desc">↘︎ 90 (14%)</div>
        </div>
      </div>
    </main>

    <div class="modal-action">
      <label for="my-modal-6" class="btn">Yay!</label>
    </div>
  </div>
</div>
