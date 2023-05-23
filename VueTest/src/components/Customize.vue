<template>
<div class="customizeSection">
    <div class="customizeSection-wrapper">
        <p class="customizeSection-title mb55 mt55">Customize your &nbsp<span>cards</span>&nbsp as you like</p>
        <div class="customizeSection-profileLayout">
            <div class="customizeSection-coral w33 dfcenter"><img src="../assets/vCard-1.png" alt="vCard1"></div>
            <div class="customizeSection-blue w33 dfcenter"><img src="../assets/UserPage.png" alt="vCard2"></div>
            <div class="customizeSection-pink w33 dfcenter"><img src="../assets/vCard.png" alt="vCard3"></div>
        </div>
        <a class="customizeSection-Link mt55 mb55" href="#">Create your own &rarr;</a>
    </div>
</div>
</template>

<script>
export default{
    name: "Customize"
}
</script>

<style>
.customizeSection{
    display: flex;
    justify-content: center;
    background-color: rgb(234, 234, 234);
    width: 100%;
    height: 900px;
}
.customizeSection-wrapper{
    width: 80%;
    display: flex;
    flex-direction: column;
}
.customizeSection-title{
display: flex;
justify-content: center;
width: 100%;
font-family: 'Roboto';
font-style: normal;
font-weight: 400;
font-size: 35px;
line-height: 47px;
color: #000000;
}
.customizeSection-title span{
color: #FFDC27;
}
.customizeSection-profileLayout{
    width: 100%;
    display: flex;
    height: 694px;
}
.mb55{
margin-bottom: 55px;
}
.mt55{
margin-top: 55px;
}
.w33{
    width: 33%;
}
.dfcenter{
display: flex;
justify-content: center;
align-items: center;
}
.customizeSection-coral{
background: #FFE8E8;
border-radius: 20px 0px 0px 20px;
}
.customizeSection-blue{
background: #ADBDDB;
}
.customizeSection-pink{
background: #FFE2EA;
border-radius: 0px 20px 20px 0px;
}
.customizeSection-Link{
display: flex;
justify-content: center;
font-family: 'Roboto';
font-style: normal;
font-weight: 400;
font-size: 20px;
line-height: 20px;
text-decoration-line: underline;
color: #000000;

}


</style>