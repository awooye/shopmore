<template>
    <div class="footer">
        <div class="footer-logo">
            <img src="/imgs/logo-footer.png" alt="">
            <p>小米商城</p>
        </div>
        <div class="footer-link">
            <a href="https://www.imooc.com/t/1343480" target="_blank">河畔一角主页</a><span>|</span>
            <a href="https://coding.imooc.com/class/113.html" target="_blank">Vue全栈课程</a><span>|</span>
            <a href="https://coding.imooc.com/class/397.html" target="_blank">React全家桶课程</a><span>|</span>
            <a href="https://coding.imooc.com/class/343.html" target="_blank">微信支付专项课程（H5+小程序+Node+Mongo）</a>
        </div>
        <div class="copyright">
            Copyright ©2019 <span class="domain">mi.futurefe.com</span> All Rights Reserved
        </div>
    </div>
</template>
<script>
export default {
    name:'nav-footer'
}
</script>
<style lang="scss" scoped>
@import "./../assets/scss/config.scss";
.footer{
    height:234px;
    background-color:#333 ;
    border-top: 4px solid #ff6600;
    color: #999;
    font-size:$fontI;
    text-align: center;
    .footer-logo{
        margin-top: 46px;
        margin-bottom: 31px;
    }
    img{
        width:53px;
        height:36px;
        margin-bottom: 13px;
    }
    .footer-link{
        a{
            color:#999;
            display: inline-block;
        }
        span{
            margin: 0 10px;
        }
        margin-bottom: 13px;
    }
    .copyright{
        .domain{
            color:#ff6600;
        }
    }
}
</style>