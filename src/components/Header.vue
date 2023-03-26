<script setup></script>
<template>
    <div class="header">
        <div class="flex-wrap">
            <div>menu</div>
            <div>info</div>
        </div>
        
    </div>
</template>
<style lang="scss" scoped>
.header { 
    display: absolute;
    top : 0px;
    left : 0px;
    padding: 0px;
    height : 24px;
    border-bottom: dotted 1px #ccc;
}

.flex-wrap{
    display: flex;
    justify-content: space-between;
}
</style>