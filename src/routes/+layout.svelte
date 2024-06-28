<script lang="ts">
	import "../app.css";
	import { page } from '$app/stores';
</script>

<nav class="flex justify-center my-6">
	<ul class="flex flex-col mt-4 font-medium lg:flex-row lg:space-x-8 lg::mt-0 text-3xl">
		<a href="#">
			My Tech Stack
		</a>
		<a href="#">
      My Projects
		</a>
	</ul>
</nav>

<div class="min-h-screen flex flex-col">
	<slot />
</div>