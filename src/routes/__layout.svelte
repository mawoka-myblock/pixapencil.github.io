<script>
	import '../app.css';
	import Navbar from '../lib/navbar.svelte';
</script>

<div class="min-h-screen min-w-full bg-gradient-to-b from-[#00b09b] via-[#50be6f] to-[#83c653]">
	<Navbar />
	<slot />
</div>
