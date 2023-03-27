<!DOCTYPE html>
<html>
<head>
<title>Login Page</title>
<style>
body
form
input[type=text], input[type=password] {
padding: 10px;
margin: 5px 0 20 px 0;
display: block;
width: 100%;
border: none;
box-shadow: 0px 0px 5px grey;
}
</style>
</head>
<body>
<form>
<h2>Login</h2>
<label for="username"><b>Username</b></label>
<input type="text" placeholder="Enter Unique Username" name="username" required>
<label for="password">,b>Password</b></label>
<input type="password" placeholder="Enter Password" name="password" required>
<button type="submit">Login</button>
<label>
<input type="checkbox" checked="checked" name="remember">Remember me
</label>
</form>
</body>
</html>
