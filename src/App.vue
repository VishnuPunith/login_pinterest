<template>
   <div>
      <form>
        <div>
        <div>
    <img class="logo" src="../src/assets/Untitled-1.png" alt="Logo" />
  </div>
        </div>
        <div class="title">
          <h1 style="color:black;" class="welcome">Welcome to Pinterest</h1></div>
         <div class="form-group">
        <div class="email">Email</div>
        <input type="email" autocomplete="email" id="email" placeholder="Email"  required />
      </div>
      <div class="form-group">
        <div class="password">Password</div>
                <input type="password" id="password" placeholder="Password"  required />
      </div>
<div>
     <a href="reset your password" class="link">Forgot your Password?</a>
    </div>
    
     <button type="submit">Log in</button>
     <h6 class="para">OR</h6>
     <button class="continue-with-facebook">
      <img class ="image" src="../src/assets/5a22b43e909176.0984090415122238065922.png" alt="">
        <span class="icon"><i class="fa fa-google"></i></span>
        Continue with Facebook
      </button>
     <!-- <img src="../src/assets/vprgoogle.png" class="google"> -->
     <button class="continue-with-google">
      <img class ="image" src="../src/assets/5a35540277d9e6.8445514415134443544909.png" alt="">
        <span class="icon"><i class="fa fa-google"></i></span>
        Continue with Google
      </button>
      <p class="paragraph">By continuing, you agree to Pinterest'<br>
        <a href="https://v-learning.in/terms/">Terms and condition</a> Opens a new tab and acknowledge you've read our<br>
        <a href="https://v-learning.in/terms/">Privacy Policy;</a> Opens a new tab.</p>
    </form>
  </div>  
</template>
<style>
#app {
  background-color: #4574a3;
  background-image:url("C:\Users\USER\login\src\assets\pinterestbg.png");
  background-size:cover;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  /* width: 500px;  
  height: 300px; */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 12px;
  padding: 25px;
  color: #a76969;
  
}
.h1 {
    color: black;
    font-size: 31px;
    /* padding: 1px; */
    margin-top: -18px;
}
.facebook {
    width: 14pc;
    border-radius: 21px;
    margin-top: -2pc;
}
.para{
  margin-top: 5px;
}
.signup-container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
.paragraph {
    font-size: 11px;
    letter-spacing: -1px;
}
.continue-with-google {
    display: inline-block;
    background-color: #e2e4e9;
    color: #171962;
    font-size: 14px;
    font-weight: bold;
    padding: 8px 27px;
    border: none;
    border-radius: 25px;
    border-color: black;
    cursor: pointer;
    text-align: center;
    text-decoration: none;
    margin-left: 2px;
    margin-top: 21px;
}
.continue-with-facebook {
    display: inline-block;
    background-color: #e2e4e9;
    color: #171962;
    font-size: 14px;
    font-weight: bold;
    padding: 8px 20px;
    border: none;
    border-radius: 25px;
    border-color: black;
    cursor: pointer;
    text-align: center;
    text-decoration: none;
    margin-left: 2px;
    position: absolute;
    margin-top: -22px;
}

.continue-with-google:hover {
  background-color: #357AE8;
}
.continue-with-facebook:hover {
  background-color: #357AE8;
}
.icon {
  display: inline-block;
  font-size: 20px;
  vertical-align: middle;
  margin-right: 10px;
}

.fa-google {
  color: #ffffff;
}
.image{
  width: 12px;
}


.logo {
    width: 2pc;
    margin-top: -87px;
    position: absolute;
    margin-left: -22px;
}
form {
    width: 367px;
    min-height: 396px;
    padding: 127px 10px 1px;
    background-color: #ffffff;
    border-radius: 15px;
    margin-top: 23px;
    margin-left: 29pc;
}
.link {
    margin-left: -6pc;
    font-size: 11px;
    display: block;
    margin-top: -1pc;
}
.welcome {
    margin-top: -41px;
    font-size: 32px;
    letter-spacing: -1.2px;
    font-weight: normal;
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
  font-size: 14px;
  border-radius: 8px;
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
    border-radius: 17px;
    font-size: 16px;
    font-weight: 600;
    cursor: pointer;
    margin-left: 0pc;
    margin-top: 18px;
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

