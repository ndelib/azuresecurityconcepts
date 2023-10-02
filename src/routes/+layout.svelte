<script lang="ts">
	import "../app.css"
    import CategorySidebar from "$lib/components/CategorySidebar.svelte"
    import SlideContent from "$lib/components/SlideContent.svelte"
</script>

<div class="navbar bg-base-100 space-x-12">
    <a class="btn btn-ghost normal-case text-xl">Azure Security Dojo</a>
    <div class="text-lg breadcrumbs">
        <ul>
            <li><a>Storage accounts</a></li> 
            <li><a>Challenge 1: Beginner Blonky's Blunder</a></li> 
        </ul>
    </div>
</div>

<!-- Main content goes here -->
<div class="flex space-x-4 justify-center w-full">

    <div class="flex flex-col justify-center w-full pl-4">
        <slot />
    </div>

    <div class="flex pr-4">
        <ul class="menu bg-base-200 w-96 rounded-box" style="height: calc(100vh - 164px);">
            <li>
            <h2 class="menu-title">Challenge Table of Contents</h2>
            <ul>
                <li><a href="/">Challenge brief</a></li>
                <li><a href="/entersolution">Enter Solution</a></li>
                <li><a>Quiz</a></li>
                <li><a>Guide</a></li>
            </ul>
            </li>
        </ul>
    </div>
</div>

<div class="drawer">
    <input id="my-drawer" type="checkbox" class="drawer-toggle" />
    <div class="drawer-side">
        <label for="my-drawer" class="drawer-overlay" />
        <CategorySidebar />
    </div>
</div>

<div class="flex justify-center w-full pt-5">
    <label for="my-drawer" class="btn btn-primary drawer-button">Show All Challenges</label>
</div>

<style>
</style>
