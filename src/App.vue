<template>
 <div id="app">
 <h1> Props in Vue js</h1>
 <img alt="Vue logo" src="./assets/logo.png">
<login name="user1" btn-text="welcome" />

</div>
</template>

<script>
import  login from './components/login'
export default {
  name: 'App',
  components: {
  login
 },
 data() {
 return {
 users:[
 {name:'nandu' , email:'nandu@test.com' },
 {name:'sam' , email:'sam@test.com' },
 {name:'me' , email:'me@test.com' },
 ]
 }
 }
};
</script>
import axios from "axios"
methods: {
 sign in:function() {
 

 var results=axios.post("http://localhost:3000/user",{
 name:this.name,
 password: this.password
 });
 console.log("//warning: ",results);
 if(result==201)
 .
}
 }
 }

if(results.status==201) {
window.lert('sign in Done')
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
