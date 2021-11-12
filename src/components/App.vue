
<template>
  <div class="test"> 		        
	  <nav class="navbar navbar-expand-lg navbar-light">  
		  <router-link to="/">
        <img class = "test-img" alt="Webpack" src="../../src/images/favicon.png" >
      </router-link>
      &nbsp;&nbsp;
      <div class="collapse navbar-collapse" id="navbarNav">
        <div class="navbar-nav">
            <router-link to="/">Home</router-link>&nbsp;&nbsp;
            <router-link to="/about">About</router-link>&nbsp;&nbsp;
            <router-link to="/myinfo">Per Steen Olsen</router-link>&nbsp;&nbsp;
            <router-link to="/employee">Web API</router-link>&nbsp;&nbsp;
            <router-link to="/error">Secret</router-link>
        </div>
       </div>
      </nav>
    <router-view/>
  </div>
</template>

<style lang="scss" scoped>
  $mainColor: #333;
  .test{
    width: 100%;
    height: 100%;
    background-color: $mainColor;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .test-img{
    width: 100px;
    height: 100px;
  }
</style>

