<script lang="ts">
	const spiral: string = 'out';
	$: console.log('%cspiral', 'color:red', spiral);
</script>

<div
	class="h-screen w-screen flex flex-col items-center justify-center bg-gradient-to-tr from-pink-900 to-stone-900"
>
	<h1 class="text-stone-400">Proxima</h1>
	<h1 class="text-fuchsia-700">Tauri</h1>
</div>
