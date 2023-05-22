<template>
  <div class="titlenav">
    <div class="wrapperNav">
        <nav>
          <a href="#">vCards</a>
          <a href="#">Menu</a>
          <a href="#">Coupons</a>
          <a href="#">Business page</a>
          <a href="#">Feedback</a>
          <a href="#">Rating</a>
          <a href="#">Video</a>
          <a href="#">Event</a>
        </nav>
    <div class="title"> Use&nbsp<span class="titlenav-Qrcode">QR-code</span>&nbspfor your business cards</div>

    </div>
  </div>
</template>

<script>
export default {
  name: "TitleNav",
};
</script>

<style>
.titlenav{
    background: #01021B;
    height: 214px;
    display: flex;
    justify-content: center;
}
.titlenav-Qrcode{
 color: #FFDC27;
}
.title{
display: inline-flex;
width: 100%;
width: 655px;
height: 47px;
font-family: 'Roboto';
font-style: normal;
font-weight: 400;
font-size: 40px;
line-height: 47px;
color: #FFFFFF;
margin-bottom: 30px;
align-self: center;
}
.wrapperNav{
    width: 80%;
    display: flex;
    flex-direction: column-reverse;
    height: 100%;
}
nav{
    height: 53px;
    display: flex;
    justify-content: space-between;
    width: 100%;
    margin-bottom: 30px;
}
nav a{
text-decoration: none;
font-family: 'Roboto';
font-style: normal;
font-weight: 400;
font-size: 17px;
line-height: 22px;
color: #DDDDDD;
box-sizing: border-box;
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 15px 40px;
height: 52px;
background: #01021B;
border: 1px solid #DDDDDD;
border-radius: 20px;
}
nav a:hover{
box-sizing: border-box;
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 15px 40px;
height: 52px;
background: rgba(230, 230, 230, 0.25);
border: 1px solid #DDDDDD;
border-radius: 20px;
}
</style>
