<script setup></script>
<template>
    <div class="body">

        <div class="body-wrap">
            <div class="content">달력</div>
            <div class="content">
                <button class="center">
                    🙂🙂
                </button>
            </div>
            <div class="content">
                <div class="icon-check">할일</div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.body{
    height: auto;
  min-height: 100%;
  padding-bottom: 24px;
}
.body-wrap {
    padding : 5px;
    .content { 
        display: flex;
        justify-content: center;   
    }
}

.icon-check{
    ::before{
        content:"";
        background-image: url("../assets/checkbox.png");
        background-size:100px 100px;
        width:100px;
        height:100px;
        display:inline-block;
    }
}
</style>