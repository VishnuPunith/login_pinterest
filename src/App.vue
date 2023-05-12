<template>
  <div id="app">
   <div>
      <form>
        <h1 style="color:black">Welcome to Pinterest</h1>

        <div class="form-group">
        <div class="email">Email</div>
        <input type="email" autocomplete="email" id="email" placeholder="Email"  required />
      </div>
      <div class="form-group">
        <div class="password">Password</div>
                <input type="password" id="password" placeholder="Password"  required />
      </div>
     <button type="submit">Sign Up</button>
    </form>
  </div>
  </div>   
</template>

<style>
#app {
  background-color: #4574a3;
  background-image:url("C:\Users\USER\login\src\assets\pintrest.webp");
  background-repeat: no-repeat;
  background-size: cover;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  /* width: 500px;  
  height: 300px; */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 12px;
  color: #a76969;
  
}
.signup-container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

form {
    width: 377px;
    min-height: 396px;
    padding: 127px 10px 1px;
    background-color: #efe7e7;
    border-radius: 37px;
    margin-top: -29px;
    margin-left: 21pc;
}

.email {
    text-align: left;
    font-size: smaller;
    margin-left: 80px;
}
.password {
    font-size: smaller;
    margin-left: -157px;
    margin-top: -1rem;
    
}
.form-group {
  margin-bottom: 20px;
  border-radius: 3rem;
}

label {
  display: block;
  font-weight: 600;
  margin-bottom: 10px;
}

input[type="text"],
input[type="firstname"],
input[type="email"],
input[type="password"],
input[type="passwordConfirm"]
{
  width: 55%;
  padding: 9px;
  font-size: 16px;
  border-radius: 15px;
  font-style: Poppins;
  border: 1px solid lightgray;
  margin: 0;
}

button[type="submit"] {
    width: 61%;
    padding: 8px;
    background-color: rgb(185, 25, 25);
    color: white;
    border: none;
    border-radius: 8px;
    font-size: 16px;
    font-weight: 600;
    cursor: pointer;
    margin-left: 0pc;
}
background-image
{
  opacity: inherit;
}


.navbar{
  display: flex;
}


.nav{
  display: flex;
}
.img{
    width: 30rem;
    height: 40rem;
  }
  .content{
    display: flex;
    
  }
.img-content{
  width:13%;
  margin-left: 125px;
 
}
button{
  margin-left: 40px; 
}
.nav .button{
  display: flex;
  align-items: flex-end;
  margin-left: 30rem;
}
.el-card{
  width: 65rem;
  border-radius: 18px;
  margin-left: 125px;

}
.buttonsign{
  border-radius: 20px;
   font-style: Poppins;
}
.footer-item{
  font-style: Poppins;
}
.footer-link
{
  font-style: Poppins;
}
.pagesame{
  font-style: Poppins;
  margin-left: 12px;
}
</style>
