<div class="container mx-auto mt-10" style="width:100% height:50vh">
    <div
        class="grid grid-cols-3 grid-rows-4 gap-4 sm:overflow-x-auto"
        style="width: 100%; height:100%;"
    >
        <div class="newsCard row-span-2">
            <div class="imgContainer1">
                <img src="/mongodb-icon.svg" alt="" />
            </div>
            <div class="newsContent">
                <h2>Can coffee make you a better developer?</h2>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                    Voluptatibus quia, nulla! Maiores et perferendis eaque,
                    exercitationem praesentium nihil.
                </p>
            </div>
        </div>
        <div class="newsCard col-span-2">
            <div class="imgContainer2">
                <img src="/mongodb-icon.svg" alt="" />
            </div>
        </div>
        <div class="newsCard col-span-2">
            <div class="imgContainer2">
                <img src="/mongodb-icon.svg" alt="" />
            </div>
        </div>
        <div class="newsCard col-span-2">
            <div class="imgContainer2">
                <img src="/mongodb-icon.svg" alt="" />
            </div>
        </div>
        <div class="newsCard row-span-2">
            <div class="imgContainer1">
                <img src="/mongodb-icon.svg" alt="" />
            </div>
        </div>
        <div class="newsCard col-span-2">
            <div class="imgContainer2">
                <img src="/mongodb-icon.svg" alt="" />
            </div>
        </div>
    </div>
</div>

<style>
    h2 {
        @apply text-lg font-semibold;
    }
    p{
        @apply text-gray-600;
    }
    .imgContainer1 {
        @apply justify-center;
    }
    .imgContainer1 img {
        @apply justify-center;
        width: 100%;
    }
    .imgContainer1 {
        @apply justify-start;
    }
    .newsCard {
        @apply border-2 border-slate-600 rounded-lg shadow-md;
        min-height: 80px;
        width: 100%;
    }
    .newsCard .newsContent {
        @apply border-t-2 border-slate-600 text-center p-3;
        width: 100%;
        height: 100%;
    }
    .newsCard div img {
        height: 150px;
    }
</style>
