<script>
	import AsideMenu from "$lib/components/AsideMenu.svelte";
</script>

<div id="app" class="relative h-screen p-2.5 gap-1 flex flex-row bg-black">
    <aside class="rounded-l-lg w-[250px] h-full overflow-y-auto">
        <AsideMenu />
    </aside>

    <main class="flex-1 flex flex-col justify-between rounded-r-lg overflow-y-auto">
        <div class="mt-0">
            MAIN
        </div>
        <footer class="fixed pb-2 rounded-b-lg inset-x-2 bottom-2 h-24 border-t-4">
            PLAYER
        </footer>
    </main>
</div>

<style>
    aside {
        background-color: #ffc78b;
    }

    main {
        background-color: #f8d9b7;
    }

    footer {
        background-color: #d61355;
        border-style: solid;
        border-color: black;
    }
</style>