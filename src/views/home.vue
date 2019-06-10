<template>
    <div class="wrap">
        <header class="header">
            头部
        </header>
        <main class="main">
            我是主页
        </main>
        <footer class="footer">
            页脚
        </footer>
    </div>
</template>
<script>
export default {
    props:{

    },
    components:{

    },
    data(){
        return {

        }
    },
    computed:{

    },
    methods:{

    },
    created(){

    },
    mounted(){

    }
}
</script>
<style scoped lang="">
    .wrap{
        width: 100%;
        height: 100%;
        display: flex;
        flex-direction: column
    }
    .wrap .header{
        width: 100%;
        height: 44px;
        border-bottom: 1px solid #ccc;
        text-align: center;
        line-height: 44px;
    }
    .wrap .main{
        flex: 1;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .wrap .footer{
        width: 100%;
        height: 44px;
        border-top: 1px solid #ccc;
        text-align: center;
        line-height: 44px;
    }
</style>