<div class="container mx-auto mt-10" style="width:100% height:50vh">
    <div
        class="grid grid-cols-3 grid-rows-4 gap-4 sm:overflow-x-auto"
        style="width: 100%; height:100%;"
    >
        <div class="newsCard row-span-2">
            <div><img src="/mongodb-icon.svg" alt="" /></div>
            <div class="newsContent"><h2>Title</h2></div>
        </div>
        <div class="newsCard col-span-2">
            <div><img src="/mongodb-icon.svg" alt="" /></div>
        </div>
        <div class="newsCard col-span-2">
            <div><img src="/mongodb-icon.svg" alt="" /></div>
        </div>
        <div class="newsCard col-span-2">
            <div><img src="/mongodb-icon.svg" alt="" /></div>
        </div>
        <div class="newsCard row-span-2">
            <div><img src="/mongodb-icon.svg" alt="" /></div>
        </div>
        <div class="newsCard col-span-2">
            <div><img src="/mongodb-icon.svg" alt="" /></div>
        </div>
    </div>
</div>

<style>
    .newsCard {
        @apply border-2 border-slate-600 rounded-lg text-center;
        min-height: 80px;
        width: 100%;
    }
    .newsCard .newsContent {
        @apply border-t-2 border-slate-600 justify-start;
        width:100%;
        height: 100%;
    }
    .newsCard .row-span-2 div {
        @apply flex justify-center;
    }
    .newsCard div img {
        width: 100%;
        height: 150px;
    }
</style>
