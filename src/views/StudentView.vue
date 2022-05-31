<template>
<!--<img class = "logo" src = "../assets/hat.png" />-->
<h1>Student Login</h1>
<div class="student">
    <input type="text" v-model="email" placeholder="Enter Email" />
    <input type="password" v-model="password" placeholder="Enter Password" />
   <router-link to="/studentDashboard"><button v-on:click="login">Login</button></router-link> 
</div>
</template>

<style>
.logo{
    width:100px
}
h1{
  text-align: center;
}

.student input{
    width: 300px;
    height: 40px;
    padding-left: 20px;
    display: block;
    margin-block: 30px;
    margin-right: auto;
    margin-left: auto;
    border: 1px solid skyblue;
}
.student button{
    width: 150px;
    height: 40px;
    border: 1px solid lightskyblue;
    background: deepskyblue;
    color: #FFFF;
    cursor: pointer;
    margin-block: 30px;
    margin-right: auto;
    margin-left: 565px;
}


</style>