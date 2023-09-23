<script lang="ts">
	import CategorySidebar from "$lib/components/CategorySidebar.svelte";
	import SlideContent from "$lib/components/SlideContent.svelte";
</script>

<div class="navbar bg-base-100">
	<a class="btn btn-ghost normal-case text-xl">Azure Security Concepts</a>
</div>

<!-- Main content goes here -->
<div class="flex space-x-4 justify-center w-full">

	<div class="flex flex-col justify-center w-full pl-4">
		<SlideContent />
		<progress class="progress progress-accent w-full -top-2" value="30" max="100"></progress>
	</div>

	<div class="flex pr-4">
		<ul class="menu bg-base-200 w-56 rounded-box" style="height: calc(100vh - 164px);">
			<li>
			<h2 class="menu-title">Title</h2>
			<ul>
				<li><a>Item 1</a></li>
				<li><a>Item 2</a></li>
				<li><a>Item 3</a></li>
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
