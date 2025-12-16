<script>
	import { marked } from "marked";
	import my_markdown from "$lib/posts/POST.md?raw";
</script>
<main>
	<article class="prose">
		<h1>The Player Hater Piano</h1>
        <div class="badge badge-outline badge-primary">Scribbled: November 11th, 2037</div>
        {@html marked(my_markdown)}
				<div class="text-center">
			<span class=" text-rotate text-center text-7xl duration-4000">
				<span class="justify-items-center">
					<span>NED LUDD</span>
					<span>DID</span>
					<span>NOTHING</span>
					<span>WRONG</span>
				</span>
			</span>
		</div>
	</article>
</main>

<style>
	article {
		margin: auto;
		min-width: 60%;
		padding-top: 5%;
		padding-bottom: 5%;
	}
</style>
