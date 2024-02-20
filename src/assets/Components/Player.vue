<script setup>


</script>

<template>
    <div class="w-auto bg-white text-black m-10 p-20  rounded-3xl">
        <div class="flex p-15 justify-between align-center">
            <select id="readingDepth" name="readingDepth">
                <option value="x1">Depth</option>
                <option value="x1">x1</option>
                <option value="x5">x5</option>
                <option value="x20">x20</option>
                <option value="x50">x50</option>
                <option value="x100">x100</option>
            </select>           
    
            <img class="w-10 h-10" src="../images/rewind.png" alt="">
            <img class="w-10 h-10" src="../images/pause.png" alt="">
            <img class="w-10 h-10" src="../images/play.png" alt="" hidden>
            <img class="w-10 h-10" src="../images/forward.png" alt="">
            <div>
                <img class="w-10 h-10" src="../images/multiply.png" alt="">
                <p>speed</p>
            </div>
            
        </div>
    </div>
</template>