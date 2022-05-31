<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
<pre>


<router-link to="/admin"><button>Admin Login</button></router-link>



<router-link to="/student"><button>Student Login</button></router-link>



<router-link to="/faculty"><button>Faculty Login</button></router-link>


</pre>


  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1{
  color: #004600;
  font-size: 4rem;
}
button {
  background-color: #006747;
  color: white;
  font-size: 16px;
  width: 400px;
  height: 50px;
  font-size: 1.5rem;
  font-style: italic;
}
button:hover {
  background-color: #008CBA;
  color: white;
}
.hello{
  text-align: center;
}
</style>
