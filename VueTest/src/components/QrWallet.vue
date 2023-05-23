<template>
<div class="qrWallet">
    <div class="qrWallet-wrapper">
        <p class="mb55 mt55">Save your cards directly on Apple and Google Wallet</p>
        <div class="qrWallet-phonePhoto"><img src="../assets/iPhone-13-Pro-Front.png" alt="iphone">
            <a href="#" class="qrWallet-getStarted mt55 mb55">Get started &rarr;</a>
        </div>
    </div>
    <img src="../assets/Rectangle 422.png" class="qrWallet-img" alt="rect">
</div>
</template>

<script>
export default{
    name:"QRWallet"
}
</script>

<style>

.qrWallet{
width: 100%;
height: 850px;
display: flex;
justify-content: center;

}

.qrWallet-wrapper{
    z-index: 9999;
width: 80%;
display: flex;
justify-content: center;
flex-direction: column;    
}
.qrWallet-wrapper p{
display: flex;
justify-content: center;
width: 100%;
height: 47px;
font-family: 'Roboto';
font-style: normal;
font-weight: 400;
font-size: 35px;
line-height: 40px;
color: #000000;
}
.qrWallet-phonePhoto
{
    height: 700px;
    display: flex;
    justify-content: center;
    flex-direction: column;
    align-items: center;
}
.qrWallet-phonePhoto img {
    height: 600px;
    width: 298px;
}
a.qrWallet-getStarted{
font-family: 'Roboto';
font-style: normal;
font-weight: 500;
font-size: 30px;
line-height: 35px;
color: #FFFFFF;
text-decoration: none;

}
.qrWallet-img{
    width: 100%;
    height: 350px;
    align-self: end;
    position: absolute;
}


</style>