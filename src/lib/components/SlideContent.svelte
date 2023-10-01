<script lang="ts">
    import Challenge1 from "$lib/components/challenge1/Challenge1.svelte"
    export let curSlide
</script>

<!-- <div class="flex justify-center w-full" style="height: calc(100vh - 164px);">
    Authentication and Authorization is really cool man.
</div> -->

{#if curSlide == "challenge1"}
    <Challenge1/>
{:else}
    <div class="hero bg-base-200 rounded-box" style="height: calc(100vh - 164px);">
        <div class="hero-content text-center">
        <div class="max-w-md">
            <h1 class="text-5xl font-bold">Hello there</h1>
            <p class="py-6">Provident cupiditate voluptatem et in. Quaerat fugiat ut assumenda excepturi exercitationem quasi. In deleniti eaque aut repudiandae et a id nisi.</p>
            <button class="btn btn-primary">Get Started</button>
        </div>
        </div>
    </div>
{/if}

<style>
</style>
