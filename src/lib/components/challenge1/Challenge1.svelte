<script lang="ts">
    import hacker1 from '$lib/assets/hacker1.jpg'
</script>

<div class="grid grid-cols-1 md:grid-cols-2 gap-10 justify-center bg-base-200 w-full rounded-box p-10" style="height: calc(100vh - 164px);">

  <div class="card bg-base-100 shadow-xl">

    <div class="avatar">
      <div class="w-full mask mask-hexagon">
        <img src="{hacker1}" />
      </div>
    </div>
  </div>

  <div class="card bg-base-100 shadow-xl">
    <div class="card-body w-full">
      <h2 class="card-title">Brief</h2>
      <p>If a dog chews shoes whose shoes does he choose? If a dog chews shoes whose shoes does he choose?If a dog chews shoes whose shoes does he choose?If a dog chews shoes whose shoes does he choose?If a dog chews shoes whose shoes does he choose?If a dog chews shoes whose shoes does he choose?</p>
      <h2 class="card-title">Difficulty</h2>
        <div class="badge badge-info gap-2 mt-2">
          Beginner
        </div>
        <p></p>
      <h2 class="card-title">Skills Learned</h2>
      <div class="text-left justify-start">
        <label class="cursor-pointer label justify-start gap-4">
          <input type="checkbox" checked="checked" class="checkbox checkbox-secondary" />
          <span class="label-text">Secure storage account authentication</span>
        </label>
        <label class="cursor-pointer label justify-start gap-4">
          <input type="checkbox" checked="checked" class="checkbox checkbox-secondary" />
          <span class="label-text">Defense in depth</span>
        </label>
        <label class="cursor-pointer label justify-start gap-4">
          <input type="checkbox" checked="checked" class="checkbox checkbox-secondary" />
          <span class="label-text">Layer 7 vulnerabilities</span>
        </label>
      </div>
      <p></p>
      <div class="card-actions justify-center">
        <button class="btn btn-primary">Try Challenge</button>
      </div>
    </div>
  </div>

</div>

<!-- <div class="hero bg-base-200 rounded-box" style="height: calc(100vh - 164px);">
    <div class="flex justify-between w-full transform -translate-y-1/2 left-5 right-5 top-1/2 pr-4 pl-4">
      <a href="#" class="btn btn-circle btn-outline">❮</a> 
      <a href="#" class="btn btn-circle btn-outline">❯</a>
    </div>
    <div class="hero-content text-center">
      <div class="max-w-md">
        <article class="prose prose-xl">
          Beginner blonky made a blunder. What a derpy head.
        </article> 
      </div>
    </div>
</div> -->

<style>
</style>
