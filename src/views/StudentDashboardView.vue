<template>
  <div class="studentDashboard">
  <h1>Internship Management System</h1>
  <ul>
  
  <li style="float:right"><router-link to="/"><button id="logout" class="active">Logout</button></router-link></li>  
</ul>
   <div class="same">
    <span name="search" id="search" style="margin-left:200px">Search <input type="text" style="margin-left:10px"/></span>
    
    </div>
    <div class="cards">
    <button name="internshipApplicationForm">Internship<br/>Application<br/>Form</button>
    <router-link to="/studentDetails"><button name="studentDetails" style="margin-left:100px;">Student Details</button></router-link>
    </div>
  </div>
</template>
<!--
<script>
export default {
  name: 'StudentDashboard',
  methods:{
    goToLoginPage(){
        this.$router.push('/student'); 
    }
  }
}
</script>
-->

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,h2 {
  color: #004600;
  text-align: center;
}
.same{
    display:inline-block;
}
span {
  color: black;
}
#search{
    font-size: 1.3rem;
    color: #004600;
}
button {
  background-color: #FFFFFF;
  border: 2px solid #FFFFFF;
  border-radius: 12px;
  padding-top: 15px;
  padding-bottom: 15px;
  padding-left: 15px;
  padding-right: 15px;
}
#logout{
    width: 90px;
    height: 40px;
    border: 1px solid lightskyblue;
    background: #004600;
    color: #FFFF;
    cursor: pointer;
    margin-block: 30px;
    margin-left: 565px;
    text-align: center;
    padding-top: 10px;
    font-style: bold;
}

ul {
  list-style-type: none;
  overflow: hidden;
  background-color: deepskyblue;
  padding-top: 5px;
  padding-bottom: 5px;
}

li {
  float: left;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover:not(.active) {
  background-color: #111;
}

.active {
  background-color: #04AA6D;
}
</style>