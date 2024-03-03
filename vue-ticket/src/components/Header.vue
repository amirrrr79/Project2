<template>
  <header class="header">
     <div class="icon">
        <p><i class="bi bi-vimeo ms-2"></i>مستر بلیط</p>
     </div>
        <ul class="links">
            <router-link :to="{name:'plane'}"><li class="link"><i class="bi bi-airplane ms-2"></i>هواپیما</li></router-link>
            <router-link :to="{name:'train'}"><li class="link"><i class="bi bi-train-front ms-2"></i>قطار</li></router-link>
            <router-link :to="{name:'bus'}"><li class="link"><i class="bi bi-bus-front ms-2"></i>اتوبوس</li></router-link>
            <router-link :to="{name:'hotel'}"><li class="link"><i class="bi bi-buildings ms-2"></i>هتل</li></router-link>
        </ul>
     
               
                  
                  <ul ul class="login">
                  <li class="log"><i class="bi bi-person-plus ms-2"></i><router-link :to="{name:'register'}">ثبت نام</router-link></li>
                  <li class="log"><i class="bi bi-person ms-2"></i><router-link :to="{name:'login'}" >ورود</router-Link></li>
                 </ul>
            
      
     


  </header>
</template>

<script setup>
 


</script>

<style scoped>
 .header{
    display: flex;
    justify-content: space-around;
    align-items: center;
    border-bottom: 1px solid white;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
    border-radius:0% 0% 10% 10%;
    background-color: white;
   
 }
 
 .links{
    display: flex;
    margin-right: 3rem;
 }
  ul a li{
   text-decoration: none;
 }
 .link{
  margin-left: 3rem;
 }
 .links li{
    color: #617d98;
 }
 .links a{
   text-decoration: none;
   font-weight: bold;
   margin-right: 1.5rem;
 }
 .login{
    display: flex;
 }
 .log{
    margin-left: 2rem;
 }
 .icon .bi{
   color: #ffc107;
   font-size:3rem
 }
 .icon p{
    font-weight: bold;
    color: black;
    font-size: 1.5rem;
 }
 .login li a{
    text-decoration: none;
    color:#617d98;
    font-weight: bold;
 }
 .links a li:hover{
   color:#ffc107;
   transition: .7s;
 }
 .login li a:hover{
   color: #ffc107;
   transition: .7s;
 }
</style>