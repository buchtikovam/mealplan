<script>
    import DayButton from "$lib/components/DayButton.svelte";
</script>

<div class="h-dvh w-dvh bg-violet-50 py-8 md:py-12">
    <div class="w-[90%] max-w-[1000px] mx-auto h-full">
        <div class="flex flex-col text-violet-950">
            <h1 class="text-2xl md:text-3xl font-bold mb-4">Vítej v BuchtišnPro, človíčku!</h1>
            <p>Asi by tě zajímalo, co budeme vařit?</p>
        </div>

        <div class="mt-4">
            <p class="font-bold text-xl text-violet-950">Jídelníček</p>

            <div class="bg-white mt-2 p-4 rounded-lg flex gap-4 w-full overflow-auto">
                <DayButton />
                <DayButton />
                <DayButton />
                <DayButton />
                <DayButton />
                <DayButton />
                <DayButton />
            </div>
        </div>


    </div>

</div>
