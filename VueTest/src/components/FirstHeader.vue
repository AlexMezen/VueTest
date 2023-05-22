<template>
  <div class="header">
    <div class="wrapper">
      <div class="left">
        <div class="logo">
          <img src="../assets/logo.png" alt="logo" />
          />
        </div>
        <div class="qr">
          <p class="qrGen">QR Code Generator</p>
          <p class="qrFree">Create your QR code for free</p>
        </div>
        <div class="createBy">
          <span class="by">by</span>
          <span class="L2QR">L2QR</span>
        </div>
      </div>
      <div className="right">
        <a class="font-href" href="#resourcing"
          ><span class="href-link">Resourcing</span></a
        >
        <a class="font-href" href="#pricing"
          ><span class="href-link">Pricing</span></a
        >
        <a class="font-href" href="#blog"
          ><span class="href-link">Blog</span></a
        >
          <a class="font-href" href="#sign Up"
            ><span class="href-link-hov">Sign Up</span></a
          >
          <a class="font-href" href="#log in"
            ><span class="href-link-hov">Log in</span></a
          >
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FirstHeader",
};
</script>

<style>
.ted{
  width: 100%;
  display: inline-flex;
  justify-content: space-between;
}

p {
  margin: 0;
}
span .href-link {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 500;
  font-size: 17px;
  line-height: 20px;
  color: #ffffff;
}

.right a:last-child:hover,
.right a:nth-child(4):hover
{
  display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 3px 15px;
color: #1e2a35;
width: 107px;
height: 39px;
background: #FFFFFF;
border-radius: 3px;
}
.right a:nth-child(4), .right a:nth-child(4):hover{
  margin-right: 30px;
}
.right a:last-child,
 .right a:nth-child(4)
{
box-sizing: border-box;
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 3px 15px;
gap: 10px;
width: 107px;
height: 39px;
border: 1px solid #FFFFFF;
border-radius: 3px;

}
.header {
  display: flex;
  justify-content: center;
  background: #01021B;  
  width: 100%;
  height: 77px;
  border-bottom: 1px solid rgba(255, 255, 255, 0.2);
}
.logo {
  padding-right: 15px;
}
.left {
  display: inline-flex;
  justify-content: flex-start;
}
.left > p {
  color: white;
}

.qrGen {
  width: 146px;
  height: 20px;
  font-family: "Roboto";
  font-style: normal;
  font-weight: 500;
  font-size: 17px;
  line-height: 20px;
  color: #ffffff;
  flex: none;
  order: 0;
  flex-grow: 0;
  padding-bottom: 5px;
}
.qrFree {
  width: 126px;
  height: 12px;
  font-family: "Roboto";
  font-style: normal;
  font-weight: 400;
  font-size: 10px;
  line-height: 12px;
  color: #dddddd;
  flex: none;
  order: 1;
  flex-grow: 0;
}
.createBy{
  display: inline-flex;
  align-self: center;
}
.L2QR {
  width: 36px;
  height: 19px;
  font-family: "Gemunu Libre";
  font-style: normal;
  font-weight: 800;
  font-size: 17px;
  line-height: 19px;
  text-align: right;
  color: #ffdc27;
}
.by{
font-family: 'Roboto';
font-style: normal;
font-weight: 400;
font-size: 10px;
line-height: 15px;
text-align: right;
color: #FFFFFF;
flex: none;
order: 0;
flex-grow: 0;
padding-right: 5px;
align-self: flex-end;
}
.right {
  display: flex;
  justify-content: space-between;
}

.font-href {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 500;
  font-size: 17px;
  line-height: 20px;
  color: #ffffff;
  flex: none;
  order: 0;
  flex-grow: 0;
}
.right a {
  padding: 10px 30px;
  text-decoration: none;
}

.wrapper {
  width: 80%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.wrapper a {
  padding-top: 10px;
  color: white;
}
</style>
