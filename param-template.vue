<template>
    <div class="parametr-container">
        <div class="text_parametr"><p>TEXT HERE</p></div>
        <div class="value-parametr-block">
            <div><p id="Temp-Press-Style">PARAM HERE</p></div>
            <div class="temp_ed">°C</div>
        </div>
        <div class="border_div"></div>
    </div>
</template>

<script>
    export default {
        props: ['text','param']
    }
</script>