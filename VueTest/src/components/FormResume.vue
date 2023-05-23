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
                                <div class="labels-image">
                                    <div class="labels-text">Image:</div>
                                </div>
                                <div class="labels-personalInfo">
                                    <div class="labels-text">Name:</div>
                                    <div class="labels-text">Numbers:</div>
                                </div>
                                <div class="labels-email">
                                    <div class="labels-text">Email:</div>
                                    <div class="labels-text">Company:</div>
                                    <div class="labels-text">Adress:</div>
                                </div>
                                <div class="labels-about">
                                    <div class="labels-text">Links:</div>
                                    <div class="labels-text">About:</div>
                                </div>
                            </div>
                            <div class="userdata">
                                <div class="userdata-userphoto">
                                    <img src="../assets/Ellipse 7.png"/>
                                    <button class="userphoto-uploadButton">Upload</button>

                                </div>
                                <div class="userdata-userinput">
                                    <form>
                                        <div class="twoblocks mb12">
                                            <input class="inputstyle" type="text" placeholder="Name"><input class="inputstyle" type="text" placeholder="Surname">
                                        </div>
                                        <input type="text" class="oneblock mb12 inputstyle" placeholder="Number">
                                        <div class="twoblocks mb12">
                                            <input class="inputstyle" type="text" placeholder="Phone"><input class="inputstyle" type="text" placeholder="Fax">
                                        </div>
                                        <input type="text" class="oneblock mb12 inputstyle" placeholder="Number">
                                        <div class="twoblocks mb12">
                                            <input class="inputstyle" type="text" placeholder="Occupation"><input class="inputstyle" type="text" placeholder="Company">
                                        </div>
                                        <input type="text" class="oneblock mb12 inputstyle" placeholder="Adress">
                                        <div class="userdata-linkwrapper">
                                            <a href="#">Enter adress</a>
                                        </div>
                                        <input type="text" class="oneblock mb12 inputstyle" placeholder="Links">
                                        <input type="text" class="oneblock mb12 inputstyle" placeholder="About">
                                    </form>
                                </div>
                                
                            </div>
                        </div>
                        <div class="MoreCustomization"><a href="#">More customization</a> &rarr;</div>
                </div>
                <div class="vCard-right">
                    <img src="../assets/UserPage.png" alt="userpage">
                    <form class="right-formemail">
                        <label for="EmailAdress" class="mb12">Email adress</label>
                        <input type="text" class="oneblock mb12 inputstyle" name="EmailAdress" id="EmailAdress" placeholder="Email">
                        <button class="userphoto-uploadButton oneblock">Share with a Qr code</button>
                    </form>
                </div>
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
.userdata{
    width: 100%;
    height: 100%;
}
.userdata-userphoto{
    margin-top: 30px;
    margin-bottom: 15px;
    display: flex;
    align-items: center;
    
}
.userdata-userphoto img{
    margin-right: 50px;
}
.mb12{
margin-bottom: 12px;
}
.userphoto-uploadButton{
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 10px 30px;
gap: 10px;
width: 114px;
height: 38px;
background: #FFDC27;
border-radius: 3px;
font-family: 'Roboto';
font-style: normal;
font-weight: 400;
font-size: 17px;
line-height: 22px;
color: #000000;
}
.twoblocks{
    display: flex;
    justify-content: space-between;
}
.oneblock{
    width: 100%;
}
.twoblocks input{
    width: 49%;
}
.userdata-linkwrapper{
display: flex;
justify-content: flex-end;
align-items: center;
height: 60px;
font-family: 'Roboto';
font-style: normal;
font-weight: 400;
font-size: 13px;
line-height: 15px;
text-align: right;
text-decoration-line: underline;
color: #4B68FF;
}
.inputstyle{
box-sizing: border-box;
display: flex;
flex-direction: column;
justify-content: center;
align-items: flex-start;
padding: 8px 15px;
height: 38px;
background: #FFFFFF;
border: 1px solid #DDDDDD;
border-radius: 3px;
}
.vCard-middle{
    height: 100%;

}
.labels-image{
    margin-top: 59px;
    margin-bottom: 52px;
}
.labels-personalInfo{
    height: 66px;
    width: 100%;
    margin-bottom: 87px;
    display: inline-flex;
    flex-direction: column;
    justify-content: space-between;
}
.labels-email{
    height: 120px;
    margin-bottom: 87px;
    width: 100%;
    display: inline-flex;
    flex-direction: column;
    justify-content: space-between;
}
.labels-about{
    height: 77px;
    width: 100%;
    margin-bottom: 0;
    display: inline-flex;
    flex-direction: column;
    justify-content: space-between;
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
height: 80px;
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
.vCard-right{
    display: flex;
    flex-direction: column;
    align-items: center;
}
.vCard-right img{
    width: 258px;
    height: 515px;
    margin-top: 55px;
    margin-bottom: 30px;
}
.right-formemail{
display: flex;
flex-direction: column;
width: 258px;
font-family: 'Roboto';
font-style: normal;
font-weight: 400;
font-size: 17px;
line-height: 22px;
color: #000000;
}

</style>