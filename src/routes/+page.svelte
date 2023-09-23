<script lang="ts">
    import CategorySidebar from "$lib/components/CategorySidebar.svelte";
    import SlideContent from "$lib/components/SlideContent.svelte";
</script>

<div class="navbar bg-base-100 space-x-12">
    <a class="btn btn-ghost normal-case text-xl">Azure Security Concepts</a>
    <div class="text-lg breadcrumbs">
        <ul>
            <li><a>Authentication & Authorization</a></li> 
            <li><a>OAuth2.0 & Open ID Connect in Azure Entra ID</a></li> 
        </ul>
    </div>
</div>

<!-- Main content goes here -->
<div class="flex space-x-4 justify-center w-full">

    <div class="flex flex-col justify-center w-full pl-4">
        <SlideContent curSlide="oauth2_and_oidc"/>
        <progress class="progress progress-accent w-full -top-2" value="30" max="100"></progress>
    </div>

    <div class="flex pr-4">
        <ul class="menu bg-base-200 w-96 rounded-box" style="height: calc(100vh - 164px);">
            <li>
            <h2 class="menu-title">Table of Contents</h2>
            <ul>
                <li><a>What you'll learn here</a></li>
                <li><a>Why are OAuth2.0 & OIDC important?</a></li>
                <li><a>Intro 1: Authentication vs Authorization?</a></li>
                <li><a>Intro 2: History</a></li>
                <li><a>Problem OAuth2.0 Solves</a></li>
                <li><a>High Level Overview</a></li>
                <li><a>High Level Overview With Jargon</a></li>
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
    <label for="my-drawer" class="btn btn-primary drawer-button">Show All Concepts</label>
</div>

<style>
</style>
