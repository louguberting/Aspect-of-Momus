<script>
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>
<div class="navbar bg-base-300">
  <button class="btn btn-ghost text-xl">Aspect of Momus</button>
</div>
{@render children()}
<footer class="footer sm:footer-horizontal footer-center bg-base-300 text-base-content p-4">
  <aside>
    <p>Copyright © {new Date().getFullYear()+12} - All rights reserved by Momus</p>
	<p>Momus does not now nor has it ever promoted online falsehoods</p>
	<p>Random Disclaimer: This blog is a work of speculative fiction and if you believe it that is on you, babe.</p>
  </aside>
</footer>