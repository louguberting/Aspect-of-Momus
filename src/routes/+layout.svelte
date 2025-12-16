<script>
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={favicon} />
	<title>Aspect of Momus</title>
</svelte:head>
<div class="navbar sticky top-0 bg-base-300">
	<button class="btn text-xl btn-ghost">Aspect of Momus</button>
</div>
{@render children()}
<footer class="footer-center footer bg-base-300 p-4 text-base-content sm:footer-horizontal">
	<div class="avatar">
		<div class="mask w-24 mask-circle">
			<img class="object-top grayscale" src="Momus_Tarot.jpg" />
		</div>
	</div>
	<aside>
		<p>Copyright © {new Date().getFullYear() + 12} - All rights reserved by Momus</p>
		<p>Momus does not now nor has it ever promoted online falsehoods</p>
		<p>
			Random Disclaimer: This blog is a work of speculative fiction and if you believe it that is on
			you, babe.
		</p>
	</aside>
</footer>