<template>
    <div class="vCardSection">
        <div class="vCardSection-wrapper">
            <div class="vCard">
                <div class="vCard-form">
                    <div class="vCard-left">
                        <div class="vCard-fill">
                            <div class="vCard-contactInfo">Fill out all necessary contact information</div>
                        </div>
                        <div class="vCard-middle">
                            <div class="labels">
                                <div class="labels-text">Image:</div>
                                <div class="labels-text">Name:</div>
                                <div class="labels-text">Numbers:</div>
                                <div class="labels-text">Email:</div>
                                <div class="labels-text">Company:</div>
                                <div class="labels-text">Adress:</div>
                                <div class="labels-text">Links:</div>
                                <div class="labels-text">About:</div>
                        </div>
                        </div>
                        <div class="MoreCustomization"><a href="#">More customization</a> &rarr;</div>
                </div>
                <div class="vCard-right"></div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default{
    name: "FormResume"
}


</script>

<style>
.vCardSection{
width: 100%;
height: 1380px;
background: #01021B;
display: flex;
justify-content: center;
}
.vCardSection-wrapper{
    display: flex;
    width: 80%;
}
.vCard{
width: 100%;
height: 778px;
background: #F9F9F9;
box-shadow: 0px 2px 15px rgba(0, 0, 0, 0.15);
border-radius: 20px;
}
.vCard-form{
    /* margin-top: 40px; */
    display: flex;
    width: 100%;
    flex-direction: row;
    height: 100%;
}

.vCard-contactInfo{
display: inline-flex;
font-family: 'Roboto';
font-style: normal;
font-weight: 500;
font-size: 13px;
line-height: 15px;
color: #434343;
height: 40px;
align-items: end;
}
.vCard-left{
    display: flex;
    flex-direction: column;
    margin-left: 40px;
}
.vCard-middle{
    height: 100%;

}
.labels-text{
font-family: 'Roboto';
font-style: normal;
font-weight: 400;
font-size: 17px;
line-height: 22px;
color: #818181;
}
.MoreCustomization{

font-family: 'Roboto';
font-style: normal;
font-weight: 400;
font-size: 21px;
line-height: 25px;
color: #4B68FF;
}
.MoreCustomization a{
height: 55px;
font-family: 'Roboto';
font-style: normal;
font-weight: 400;
font-size: 21px;
line-height: 25px;
text-decoration-line: underline;
color: #4B68FF;
}

.vCard-left, .vCard-right{
width: 50%;
height: 100%;
}
.vCard, .vCard-middle, .MoreCustomization{
display: inline-flex;
}

</style>