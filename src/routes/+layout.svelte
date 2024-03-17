<script>
	import AsideMenu from "$lib/components/aside-menu.svelte";
</script>

<div id="app" class="relative h-screen p-2.5 gap-2 flex flex-row bg-black">
    <aside class="rounded-l-lg w-[250px] h-full bg-green-700 overflow-y-auto">
        ASIDE
    </aside>

    <main class="flex-1 flex flex-col justify-between rounded-r-lg overflow-y-auto bg-red-200">
        <div class="mt-0">
            MAIN
            <slot />
        </div>
        <footer class="fixed pb-2 rounded-b-lg inset-x-2 bottom-2 h-24 bg-gray-700 border-t-8 border-black">
            PLAYER
        </footer>
    </main>
</div>
