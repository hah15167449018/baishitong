<template>
    <div class="detail">
        <img src="@/img/background.png" class="img">
        <div class="detail-form">
            <img src="@/img/house.jpg" class="form-img">
            <div class="form-price">
            <ul>
                <li>工费：20元</li>
                <br>
                <li>砂浆：20元</li>
                <br>
                <li>砖胶：20元</li>
                <br>
                <li>界面剂：10元</li>
            </ul>
            </div>
            <div class="form-price">
                <ul>
                    <li>房屋面积：<input type="text" class="form-input"></li>
                    <br>
                    <li>房屋户型：<input type="text" class="form-input"></li>
                    <br>
                    <li>客户姓名：<input type="text" class="form-input"></li>
                    <br>
                    <li>手机号码：<input type="text" class="form-input"></li>
                </ul>
                <div class="btn">
                    立即提交
                </div>
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
        name: "detail"
    }
</script>

<style scoped>
    .detail-form{
        background: #ffffff;
        position: absolute;
        top:.7rem;
        left:1rem;
        right: 1rem;
        z-index: 2;
        border: .1rem solid #ffffff;
        opacity:0.9;
        filter:alpha(opacity=90);
    }
    .form-img{
        width: 100%;
    }
    .form-price{
        list-style: none;
        color: #ffffff;
        font-size: .4rem;
        margin-top: .1rem;
        padding: .4rem;
        background: #5D5F5E;
    }
    .form-input{
        width: 49%;
    }
    .btn{
        text-align: center;
        background: red;
        margin-top: .2rem;
        border-radius:.1rem;
        padding: .1rem;
    }
    .img{
        width: 100%;
        position: relative;
        z-index: 1;
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