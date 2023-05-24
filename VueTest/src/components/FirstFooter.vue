<template>
    <footer>
        <div class="footer-wrapper">
            <div class="footer-nav mt55">
                <p class="footer-linkTitle ">Legal</p>
                    <a href="#" class="footer-link mb12">About Us</a>
                    <a href="#" class="footer-link mb12">Terms and Conditions</a>
                    <a href="#" class="footer-link mb12">Privacy Policy</a>
            </div>
            <div class="footer-nav mt55">
                <p class="footer-linkTitle">Resources</p>
                    <a href="#" class="footer-link mb12">QR codes on material</a>
                    <a href="#" class="footer-link mb12">QR codes for business</a>
            </div>
            <div class="footer-nav mt55">
                <p class="footer-linkTitle">Support</p>
                    <a href="#" class="footer-link mb12">Help Center</a>
                    <a href="#" class="footer-link mb12">FAQ</a>
                </div>
            <div class="footer-nav mt55">
                <p class="footer-linkTitle">Information</p>
                    <a href="#" class="footer-link mb12">Blog</a>
                    </div>
        </div>
    </footer>
</template>

<script>
export default{
    name:"FirstFooter"
}
</script>

<style>
footer{
    width: 100%;
    height: 250px;
    display: flex;
    justify-content: center;
    background: #01021B;
}
.footer-wrapper{
    width: 80%;
    display: flex;
}
.footer-nav{
    width: 250px;
    display: flex;
    flex-direction: column;
}
.footer-linkTitle{
    font-family: 'Roboto';
font-style: normal;
font-weight: 500;
font-size: 17px;
line-height: 20px;
color: #FFFFFF;
}
.footer-link{
font-family: 'Roboto';
font-style: normal;
font-weight: 400;
font-size: 13px;
line-height: 15px;
color: #DDDDDD;
text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
text-decoration: none;
}
</style>