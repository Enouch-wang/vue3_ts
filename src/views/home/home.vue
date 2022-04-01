<template>
    <div class="home-box">
        <div class="title">简洁/实用<span>vue3.0+ts</span> 现成模板</div>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
    setup() {
        
    },
})
</script>
<style lang="scss" scoped >
    .home-box{
        text-align: center;
       .title{
           font-size: 40px;
           font-weight: 600;
           margin: 50px 0 30px;
           span{
               color: red;
           }
       }
       
    }
    @keyframes icon-svg{
        0%{
            opacity: 0.5;
        }
        50%{
           opacity: 1;
        }
        100%{
           opacity: 0.5;
        }
    }
</style>
