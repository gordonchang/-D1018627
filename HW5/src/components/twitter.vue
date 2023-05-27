<template>
  <div class="container">
    <div class="login-frame">
      <div class="login-logo">
        <img src="https://iconsplace.com/wp-content/uploads/_icons/ffffff/256/png/twitter-icon-18-256.png"
             alt="Twitter Logo">
      </div>
      <div class="login-register">
        <h2>登入 Twitter</h2>
      </div>
      <button type="submit" class="btn-google" onclick="login()">
        <img
            src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/53/Google_%22G%22_Logo.svg/2008px-Google_%22G%22_Logo.svg.png">使用Google帳戶登入
      </button>

      <button type="submit" class="btn-apple" onclick="login()">
        <img
            src="https://static.vecteezy.com/system/resources/previews/002/520/838/original/apple-logo-black-isolated-on-transparent-background-free-vector.jpg">使用Apple帳戶登入
      </button>
      <div class="or divide">
        <h3> 或</h3>
      </div>
      <HR id="line1" width="150" SIZE="5"/>
      <HR id="line2" width="150" SIZE="5"/>

      <div class="login-form">
        <div class="form-group">
          <input type="text" id="username" name="username" placeholder="電話、電子郵件或使用者名稱" required>
        </div>
      </div>

      <button type="submit" class="btn-next" onclick="alert('It is a prank!!!')">下一步</button>


      <button type="submit" class="btn-forgot" onclick="login()">忘記密碼?</button>


      <div class="non-login">
        <p>還沒有帳戶嗎? <a href="#"> 註冊</a></p>
      </div>


    </div>
  </div>
</template>

<script>
export default {};
</script>


<style scoped>
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background: #242D34;
}

.login-frame {
  display: flex;
  flex-direction: column;
  justify-content: center;
  margin: 0 auto;
  background-color: black;
  box-shadow: 0 0 10px rgba(0, 0, 0, 1);
  padding: 50px;
  border-radius: 30px;
  width: 650px;
  height: 800px;
}


img {
  max-width: 100%;
  max-height: 100%;
}

.login-logo {
  display: flex;
  justify-content: center;
  margin-bottom: 12cm;
  height: 50px;
  width: auto;
}


h2 {
  color: white;
  font-size: 50px;
  margin-top: -425px;
  font-family: sans-serif;
  position: relative;
  left: 100px;
}

.btn-google {
  width: 400px;
  border: 0;
  background-color: white;
  padding: 8px 32px;
  color: black;
  border-radius: 50px;
  font-size: 22px;
  position: relative;
  top: -350px;
  left: 125px;
}

button img {
  width: 5px;
  height: auto;
}

.btn-apple {
  width: 400px;
  border: 0;
  background-color: white;
  padding: 5px 30px;
  color: black;
  border-radius: 50px;
  font-size: 22px;
  position: relative;
  top: -310px;
  left: 125px;
}

button img {
  width: 35px;
  height: auto;
}

h3 {
  color: white;
  font-size: 30px;
  margin-top: -275px;
  font-family: sans-serif;
  position: relative;
  left: 300px;
}

#line1 {
  position: relative;
  left: 125px;
  top: -263px;
}

#line2 {
  position: relative;
  left: -140px;
  top: -280px;
}

.form-group label {
  margin-bottom: 5px;
}

input[type=text] {
  width: 60%;
  padding: 12px;
  margin: 6px;
  box-sizing: border-box;
  position: relative;
  top: -250px;
  left: 125px;
  font-size: 20px;
}

.btn-next {
  width: 400px;
  border: 0;
  background-color: white;
  padding: 10px 32px;
  color: black;
  border-radius: 50px;
  font-size: 20px;
  position: relative;
  top: -200px;
  left: 125px;
}

.btn-forgot {
  width: 400px;
  border: 0;
  background-color: white;
  padding: 10px 32px;
  color: black;
  border-radius: 50px;
  font-size: 20px;
  position: relative;
  top: -150px;
  left: 125px;
}

.non-login {
  font-size: 20px;
  color: gray;
  position: relative;
  top: -120px;
  left: 125px;

}

a {
  color: royalblue;
}
</style>