<script lang="ts">
    let solution: string
</script>

<!-- <div class="flex justify-center bg-base-200 w-full rounded-box" style="height: calc(100vh - 164px);">
    <div class="flex items-center justify-center w-full bg-base-100 shadow-xl m-10">
        Enter the contents of hello.txt: <br>
        <input type="text" placeholder="Type here" class="input input-bordered input-primary w-full max-w-xs" />
    </div>
</div> -->

<div class="flex justify-center bg-base-200 w-full rounded-box" style="height: calc(100vh - 164px);">

<div class="card w-full shadow-2xl bg-base-100 m-10">
    <div class="card-body items-center justify-center h-full">
      <form class="mx-1 mx-md-4 max-w-sm w-full"> <!-- on:submit|preventDefault="{handleLogin}">-->
          <!-- <h1 class="text-4xl font-bold mb-5">Solve Challenge<span class="text-primary">?</span></h1> -->
          <div class="form-control max-w-sm w-full">
            <label class="label">
              <span class="label-text">Enter the contents of hello.txt: </span>
            </label>
            <input type="text" placeholder="" class="input input-bordered" name="solution" bind:value="{solution}" aria-label="email" />
          </div>
          <div class="form-control mt-6">
            <button type="submit" class="btn btn-primary w-full">Solve</button>
          </div>
          <!-- <label class="label label-text-alt mt-6">
            Don't have an account? <a href="/register" class="label-text-alt link link-hover">Click here to register</a>
          </label> -->
      </form>
    </div>
  </div>

</div>

<style>
</style>
