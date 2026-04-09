<!DOCTYPE html>
<html>
<head>

<title>My Mini Website</title>

<style>

body{
font-family: Arial;
background:#111;
color:white;
text-align:center;
margin:0;
}

header{
background:#222;
padding:20px;
font-size:28px;
}

.container{
padding:40px;
}

button{
padding:12px 25px;
border:none;
background:#00bcd4;
color:white;
font-size:16px;
cursor:pointer;
border-radius:6px;
}

button:hover{
background:#0097a7;
}

#message{
margin-top:20px;
font-size:18px;
color:#90caf9;
}

footer{
margin-top:50px;
padding:15px;
background:#222;
font-size:14px;
}

</style>

</head>

<body>

<header>
Rocky's Mini Website
</header>

<div class="container">

<h2>Welcome</h2>

<p>This is my first mini web page.</p>

<button onclick="showMessage()">Click Me</button>

<p id="message"></p>

</div>

<footer>
© 2026 Rocky
</footer>

<script>

function showMessage(){

document.getElementById("message").innerText =
"Welcome to my website bro 😎";

}

</script>

</body>
</html>
