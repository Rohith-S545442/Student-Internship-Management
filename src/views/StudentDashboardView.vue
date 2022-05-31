<template>
  <div class="studentDashboard">
    <h1>Internship Management System</h1>
    <center><span style="font-size:30px" class="studentDashboard">Student Dashboard</span></center>
    <button id="logout" style="margin-left:500px;padding-top:5px;padding-bottom:5px">Logout</button><br/><br/>
    <span name="search">Search for Internships<input type="text" style="margin-left:10px"/></span><br/><br/><br/>
    <center><button name="internshipApplicationForm">Internship<br/>Application<br/>Form</button>
    <button name="studentDetails" style="margin-left:100px;">Student<br/>Details</button></center>
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
h1 {
  color: black;
}
span {
  color: black;
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
</style>