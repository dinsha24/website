<template>
  <div id="nav">
    
    <router-link class="navitem" to="/"><img src="https://www.nextbigbrand.in/wp-content/uploads/2020/01/amazon_PNG13.png" width="90" alt=""></router-link> 
    <router-link class="navitem" to="/">Home</router-link> 
    <router-link class="navitem" to="/about">About</router-link> 
    <router-link class="navitem" to="/categories">Categories</router-link>
  </div>
  <router-view/>
</template>

<style>



#nav {
  padding: 30px;
padding-top: 10px;
  float: left;
  width: 100%;
  box-shadow: 5px 10px 18px #0a0331;
  margin-bottom: 40px;
  /* position: absolute; */
}

#nav a {
  font-weight: initial;
  color: #03070a;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
.navitem{
  margin-left: 20px;
  float: left;
  text-decoration: none;
  line-height: 50px;
}
</style>
