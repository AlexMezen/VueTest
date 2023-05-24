<template>
<div class="businessCard">
    <div class="businessCard-wrapper">
        <p class="businessCard-title mt55 mb55">Digital &nbsp<span>business card</span>&nbsp is the best solution for your brand</p>
        <div class="businessCard-plan mb30">
            <div class="businessCard-left">
                <p class="businessCard-font businessCard-yellow">
                    For individuals
                </p>
                <div class="businessCard-individualsPLans mt55">

                    <div class="businessCard-cardBlock">
                        <p class="businessCard-planTitle mb12">LIGHT FARE AND NO ADS</p>
                        <p class="businessCard-planDescription mb30">For individuals just getting started with QR Codes</p>
                        <p class="businessCard-price mb12">€ 5</p>
                        <p class="businessCard-planDescription mb30">EUR per month, billed yearly</p>
                        <button class="businessCard-button mb30">Get started</button>
                        <p class="businessCard-qr"><b>3</b> Dynamics QR Cods </p>
                    </div>
                    <div class="businessCard-cardBlock">
                        <p class="businessCard-planTitle mb12">LIGHT PRO</p>
                        <p class="businessCard-planDescription mb30">For mid-scale businesses with advanced QR Code needs</p>
                        <p class="businessCard-price mb12">€ 15</p>
                        <p class="businessCard-planDescription mb30">EUR per month, billed yearly</p>
                        <button class="businessCard-button mb30">Get started</button>
                        <p class="businessCard-qr"><b>50</b> Dynamics QR Cods </p>
                    </div>
                </div>
            </div>
            <div class="businessCard-right">
                <p class="businessCard-font">
                    For businesses
                </p>
                <div class="businessCard-individualsPLans">

                    <div class="businessCard-cardBlock width45 blueborder">
                        <p class="businessCard-planTitle bgblue mb12">Most popular</p>
                        <p class="businessCard-planTitle mb12">PRO</p>
                        <p class="businessCard-planDescription mb30">For individuals just getting started with QR Codes</p>
                        <p class="businessCard-price mb12">€ 49</p>
                        <p class="businessCard-planDescription mb30">EUR per month, billed yearly</p>
                        <button class="businessCard-button mb30">Get started</button>
                        <p class="businessCard-qr"><b>250</b> Dynamics QR Cods </p>
                    </div>
                    <div class="businessCard-cardBlock width45 bgblack">
                        <p class="businessCard-planTitle fontwhite upperletter mb12 mt55">Enterprise</p>
                        <p class="businessCard-planDescription fontwhite mb30">For global leaders with security, control, and flexibility needs</p>
                        <p class="businessCard-price fontwhite mb65">Talk to us</p>
                        <button class="businessCard-button mb30">Get started</button>
                        <p class="businessCard-qr fontwhite">Unlimited QR codes </p>
                    </div>
                </div>
            </div>
        </div>
        <a class="businessCard-compare mb55" href="#">Compare all features &rarr;</a>
    </div>
</div>
</template>

<script>
export default{
    name: "BusinessCard"
}
</script>

<style>
.businessCard-compare
{
    font-family: 'Roboto';
font-style: normal;
font-weight: 400;
font-size: 21px;
line-height: 25px;
/* identical to box height */

text-decoration-line: underline;

/* light grey */

color: #DDDDDD;
}
.businessCard{
    height: 760px;
    width: 100%;
    display: flex;
    justify-content: center;
    background: #01021B;
}
.businessCard-wrapper{
    height: 100%;
    width: 80%;
    display: flex;
    flex-direction: column;
    align-items: center;
}
.businessCard-title{
font-family: 'Roboto';
font-style: normal;
font-weight: 400;
font-size: 40px;
line-height: 47px;
color: #FFFFFF;
} 
.businessCard-title span{
    color:#FFDC27
}
.businessCard-plan{
display: flex;
width: 100%;
height: 500px;
background: #FFFFFF;
border-radius: 20px;
}
.businessCard-font{
width: 100%;
height: 75px;
display: flex;
justify-content: center;
align-items: center;
font-family: 'Roboto';
font-style: normal;
font-weight: 500;
font-size: 21px;
line-height: 25px;
color: #000000;
}

.businessCard-left, .businessCard-right{
    width: 50%;
    display: flex;
    flex-direction: column;
}
.businessCard-yellow{
    background: #FFDC27;
    border-radius: 20px 0px 0px 0px;
}
.businessCard-individualsPLans{
display: flex;
height: 100%;
justify-content: space-around;
font-family: 'Roboto';
font-style: normal;
font-weight: 500;
font-size: 21px;
line-height: 25px;
text-align: center;
color: #000000;
}
.businessCard-cardBlock{
    width: 50%;
    height: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
}
.businessCard-planTitle{
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.businessCard-planDescription{
display: flex;
justify-content: center;
width: 246px;
justify-self: center;
font-family: 'Roboto';
font-style: normal;
font-weight: 400;
font-size: 17px;
line-height: 22px;
display: flex;
align-items: center;
text-align: center;
color: black;
}
.businessCard-price{
width: 100%;
height: 35px;
font-family: 'Roboto';
font-style: normal;
font-weight: 500;
font-size: 30px;
line-height: 35px;
color: #000000;
}
.businessCard-button{
display: flex;
justify-content: center;
align-items: center;
padding: 10px 30px;
width: 245px;
height: 42px;
background: #FFDC27;
border-radius: 3px;
font-family: 'Roboto';
font-style: normal;
font-weight: 400;
font-size: 17px;
line-height: 22px;
color: #000000;
}
.bgblue{
background-color: #4B68FF;
height: 33px;
font-family: 'Roboto';
font-style: normal;
font-weight: 500;
font-size: 17px;
line-height: 25px;
text-transform: uppercase;
color: #FFFFFF;
}
.bgblack{
    border-radius: 10px 10px 0px 0px;
    background: #000000;
}
.blueborder{
    box-sizing: border-box;
    border:5px solid #4B68FF;
    border-radius: 10px 10px 0px 0px;
}
.fontwhite{
    color: white;
}
.upperletter{
text-transform: uppercase;
}
.mb65{
margin-bottom: 65px;
}
.width45{
    width: 45%;
}
</style>