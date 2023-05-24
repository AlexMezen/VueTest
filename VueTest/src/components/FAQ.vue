<template>
<div class="faq">
    <div class="faq-wrapper">
        <p class="faq-title mt55 mb55">Frequently Asked Questions</p>
        <div class="accordion accordion-flush faq-accordion" id="accordionFlushExample">
  <div class="accordion-item ">
    <h2 class="accordion-header" id="flush-headingOne">
      <button class="accordion-button h85 collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne">
        What is a QR code?
      </button>
    </h2>
    <div id="flush-collapseOne" class="accordion-collapse collapse" aria-labelledby="flush-headingOne" data-bs-parent="#accordionFlushExample">
      <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the first item's accordion body.</div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="flush-headingTwo">
      <button class="accordion-button h85 collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
        How do I scan QR Codes?
      </button>
    </h2>
    <div id="flush-collapseTwo" class="accordion-collapse collapse" aria-labelledby="flush-headingTwo" data-bs-parent="#accordionFlushExample">
      <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the second item's accordion body. Let's imagine this being filled with some actual content.</div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="flush-headingThree">
      <button class="accordion-button h85 collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseThree" aria-expanded="false" aria-controls="flush-collapseThree">
        What are the benefits of using QR codes?
      </button>
    </h2>
    <div id="flush-collapseThree" class="accordion-collapse collapse" aria-labelledby="flush-headingThree" data-bs-parent="#accordionFlushExample">
      <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the third item's accordion body. Nothing more exciting happening here in terms of content, but just filling up the space to make it look, at least at first glance, a bit more representative of how this would look in a real-world application.</div>
    </div>
  </div>
</div>
    </div>
</div>
</template>

<script>
export default{
    name:"Faq"
}
</script>

<style>
.faq{
    height: 450px;
    width: 100%;
    display: flex;
    justify-content: center;
    background-color: rgb(234, 234, 234);
}
.faq-wrapper{
height: 100%;
width: 80%;
display: flex;
flex-direction: column;
align-items: center;
}
.faq-title{
font-family: 'Roboto';
font-style: normal;
font-weight: 500;
font-size: 40px;
line-height: 47px;
color: #000000;
}
.faq-accordion{
width: 100%;
height: 500px;
}
.h85{
font-family: 'Roboto';
font-style: normal;
font-weight: 500;
font-size: 21px;
line-height: 25px;
color: #434343;
height: 85px;
}
</style>