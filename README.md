# elements-classes
Website for Elements Classes
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Elements Classes</title>

<style>
body{
font-family:Arial;
margin:0;
background:#f5f5f5;
}

header{
background:#1565c0;
color:white;
text-align:center;
padding:20px;
}

nav{
background:#222;
padding:10px;
text-align:center;
}

nav a{
color:white;
margin:15px;
text-decoration:none;
font-weight:bold;
}

.container{
padding:20px;
}

.card{
background:white;
padding:20px;
margin:20px 0;
border-radius:8px;
box-shadow:0 2px 5px rgba(0,0,0,0.2);
}

button{
background:#1565c0;
color:white;
padding:10px 20px;
border:none;
border-radius:5px;
cursor:pointer;
}

footer{
background:#111;
color:white;
text-align:center;
padding:10px;
}
</style>
</head>

<body>

<header>
<h1>Elements Classes</h1>
<p>Math | Science | English Coaching</p>
</header>

<nav>
<a href="#">Home</a>
<a href="#courses">Courses</a>
<a href="#material">Study Material</a>
<a href="#homework">Homework</a>
<a href="#videos">Videos</a>
<a href="#login">Student Login</a>
<a href="#contact">Contact</a>
</nav>

<div class="container">

<div class="card">
<h2>Welcome to Elements Classes</h2>
<p>Quality coaching for Mathematics, Science and English with focus on concept clarity and student success.</p>
</div>

<div class="card" id="courses">
<h2>Courses</h2>
<ul>
<li>Mathematics</li>
<li>Science</li>
<li>English</li>
</ul>
</div>

<div class="card" id="material">
<h2>Study Material</h2>
<p>Upload PDF Notes</p>
<input type="file">
</div>

<div class="card" id="homework">
<h2>Homework Upload</h2>
<p>Students can upload homework here</p>
<input type="file">
<button>Submit</button>
</div>

<div class="card" id="videos">
<h2>Video Lectures</h2>
<iframe width="100%" height="315"
src=UCGyyGmdmiI_C91pm_1YHKFA>
</iframe>
</div>

<div class="card" id="login">
<h2>Student Login</h2>
<input type="text" placeholder="Username"><br><br>
<input type="password" placeholder="Password"><br><br>
<button>Login</button>
</div>

<div class="card" id="contact">
<h2>Contact</h2>
<p>Phone: 9373549919</p>
<p>Email: suqlainshaikh03@gmail.com</p>
<p>Address: Lakshmi Talkies, Nehru Chowk, Parli Vaijnath</p>
</div>

</div>

<footer>
<p>© 2026 Elements Classes</p>
</footer>

</body>
</html>
