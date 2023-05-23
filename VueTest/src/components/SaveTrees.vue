<template>
<div class="trees">
    <div class="trees-wrapper">
        <p class="trees-moveAway mt55 mb30">Move away from paper</p>
        <p class="trees-fromPaper mb55">Sow the first seeds of sustainability. Avoid underused physical cards, needless reprinting costs, and tedious distribution processes.</p>
        <div class="treesParent">
            <div class="trees-block"><img src="../assets/Forest.png" alt="forest">
                <div class="trees-info">
                    <p>1</p>
                    <p>Tree Saved</p>
                </div>
            </div>
            <div class="trees-block"><img src="../assets/Expensive Price.png" alt="price">
                <div class="trees-info">
                    <p>$ 9 700</p>
                    <p>Annual savings</p>
                </div>
            </div>
        </div>
        <input class="trees-range mt55 mb30" type="range" id="volume" name="volume" min="0" max="50">
        <p class="trees-digitalCards mb30"><b>50</b> Digital Business Cards</p>
        <p class="recomPlan mb55">Recommended Plan: <span class="trees-recomPlanLink"><a href="#">LIGHT FARE AND NO ADS</a></span> </p>
    </div>
</div>
</template>

<script>
export default{
    name: "SaveTrees"
}
</script>

<style>
.trees{
display: flex;
justify-content: center;
width: 100%;
height: 900px;
background-color: rgb(234, 234, 234);
}
.trees-wrapper{
    width: 80%;
    height: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.treesParent{
    width: 100%;
    height: 500px;
    display: flex;
    justify-content: space-between;
}
.trees-block{
    display: inline-flex;
    justify-content: space-evenly;
    align-items: center;
    width: 45%;
    height: 350px;
    background: #00AE11;
    opacity: 0.4;
    border-radius: 10px;
}
.trees-block img{
    width: 130px;
    height: 130px;
    display: flex;
    align-self: center;
    margin-left: 40px;
}
.trees-range {
width: 80%;
justify-self: center;
height: 20px;
background: #D9D9D9;
border-radius: 15px;
}

.trees-info{
font-family: 'Roboto';
font-style: normal;
font-weight: 600;
font-size: 40px;
line-height: 47px;
color: #78A55A;
}
.trees-moveAway{
    display: flex;
    justify-content: center;
    font-family: 'Roboto';
    font-style: normal;
    font-weight: 400;
    font-size: 40px;
    line-height: 47px;
    color: #000000;
}
.trees-fromPaper{
display: flex;
justify-content: center;
text-align: center;
width: 675px;
font-family: 'Roboto';
font-style: normal;
font-weight: 400;
font-size: 17px;
line-height: 25px;
color: #434343;
}
.trees-digitalCards{
font-family: 'Roboto';
font-style: normal;
font-weight: 500;
font-size: 25px;
line-height: 25px;
text-align: center;
color: #000000;
}
.trees-recomPlan{
font-family: 'Roboto';
font-style: normal;
font-weight: 400;
font-size: 17px;
line-height: 25px;
text-align: center;
color: #434343;
}
.trees-recomPlanLink a{
    color: #4B68FF;
    text-decoration: none;
}

</style>