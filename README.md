<html
html>d>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Login</title>

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:poppins, sans-serif;
}
body{
  min-height:100vh;
  display:flex;
  justify-content:center;
  align-items:center;
  background:linear-gradient(135deg,#1e3c72,#2a5298);
}
.container{
  width:330px;
  padding:30px;
  border-radius:20px;
  background:rgba(255,255,255,0.1);
  backdrop-filter:blur(10px);
  box-shadow:0 8px 32px rgba(0,0,0,0.3);
}
.container h2{
  text-align:center;
  color:#fff;
  margin-bottom:20px;
}
.input-box{
  position:relative;
  margin:25px 0;
}
.input-box input{
  width:100%;
  padding:10px 5px;
  background:transparent;
  border:none;
  border-bottom:2px solid #fff;
  color:#fff;
  outline:none;
}
.input-box label{
  position:absolute;
  left:5px;
  top:50%;
  transform:translateY(-50%);
  color:#ccc;
  pointer-events:none;
  transition:.3s;
}
.input-box input:focus~label,
.input-box input:valid~label{
  top:-5px;
  font-size:12px;
  color:#00c6ff;
}
.btn{
  width:100%;
  padding:12px;
  border:none;
  border-radius:25px;
  background:#00c6ff;
  color:#fff;
  cursor:pointer;
}
.links{
  text-align:center;
  margin-top:15px;
}
.links a{
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Login</title>

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:poppins, sans-serif;
}
body{
  min-height:100vh;
  display:flex;
  justify-content:center;
  align-items:center;
  background:linear-gradient(135deg,#1e3c72,#2a5298);
}
.container{
  width:330px;
  padding:30px;
  border-radius:20px;
  background:rgba(255,255,255,0.1);
  backdrop-filter:blur(10px);
  box-shadow:0 8px 32px rgba(0,0,0,0.3);
}
.container h2{
  text-align:center;
  color:#fff;
  margin-bottom:20px;
}
.input-box{
  position:relative;
  margin:25px 0;
}
.input-box input{
  width:100%;
  padding:10px 5px;
  background:transparent;
  border:none;
  border-bottom:2px solid #fff;
  color:#fff;
  outline:none;
}
.input-box label{
  position:absolute;
  left:5px;
  top:50%;
  transform:translateY(-50%);
  color:#ccc;
  pointer-events:none;
  transition:.3s;
}
.input-box input:focus~label,
.input-box input:valid~label{
  top:-5px;
  font-size:12px;
  color:#00c6ff;
}
.btn{
  width:100%;
  padding:12px;
  border:none;
  border-radius:25px;
  background:#00c6ff;
  color:#fff;
  cursor:pointer;
}
.links{
  text-align:center;
  margin-top:15px;
}
.links a{
  color:#fff;
  text-decoration:none;
  font-size:14px;
}
</style>
</head>

<body>

<div class="container">
<h2>Login</h2>
<form onsubmit="goHome(event)">
  <div class="input-box">
    <input type="text" required>
    <label>Username</label>
  </div>

  <div class="input-box">
    <input type="password" required>
    <label>Password</label>
  </div>

  <button class="btn">Login</button>

  <div class="links">
    <a href="sign.html">Create Account</a>
  </div>
</form>
</div>

<script>
function goHome(e){
  e.preventDefault();
  window.location.href = "home.html";
}
</script>

</body>
</html># Happy-
Coding for fun 
