<template>
    <div>
        <img src="@/img/home.png" class="home-img">
        <div class="middle">
            <div class="btn-text">贴砖类型</div>
            <div class="btn-index">
                <span class="iconfont" style="color: #ffffff;margin-top: .8rem;font-size: .4rem">&#xe7c2;</span>
                <router-link tag="div" to="/detail" class="btn">工装<br/><br/>1000㎡以上</router-link>
                <span class="iconfont" style="color: #ffffff;margin-top: .8rem;font-size: .4rem">&#xe7c2;</span>
                <router-link tag="div" to="/detail" class="btn">家装<br/><br/>1000㎡以下</router-link>
            </div>
        </div>
        <div class="button-text">
            <span style="font-size: .3rem">浙江百施通智能科技有限公司</span>
            <br/>
            <span class="iconfont">&#xe63e;</span>0571-56396659&nbsp;/&nbsp;159-2595-4988
            <br>
            <span style="font-size: .1rem;font-weight:normal">浙江省杭州市余杭区海曙路18号华茂科技园4号楼5层</span>
        </div>
    </div>
</template>

<script>
    export default {
        name: "home"
    }
</script>

<style scoped>
    .home-img {
        width: 100%;
    }

    .middle {
        background: #F55A24;
        width: 100%;
        padding-top: .3rem;
        padding-bottom: .3rem;
    }

    .btn-text {
        font-size: 1rem;
        text-align: center;
        color: #516C77;
        background: #CAD6EC;
        margin: 0 1.5rem 0 1.5rem;
        padding: .1rem;
        font-weight: bold;

    }

    .btn-index {
        display: flex;
        font-size: .5rem;
        color: #ffffff;
        justify-content:space-around
    }
    .btn{
        background:#CAD6EC ;
        border-radius:.1rem;
        padding: .1rem;
        margin-top: .2rem;
    }

    .button-text {
        background: #5D5F5E;
        width: 100%;
        color: #ffffff;
        text-align: center;
        padding-top: .2rem;
        font-size: .4rem;
        padding-bottom: .4rem;
        font-family: 'Trebuchet MS', Helvetica, sans-serif;
        font-weight: bold;
    }
</style>