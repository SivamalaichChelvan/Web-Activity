### Web-Activity
## Name:Sivamalaich Chelvan T
## Reg.no:212225100051
## Program:
#index.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Profile Card</title>

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="card">

    <img src="images.jpg" alt="Profile Image" class="profile-img">

    <h1>Sivamalaich Chelvan T</h1>

    <h3>Computer Science & Engineering<br>Specialization in Cyber Security</h3>

    <h2>About Me</h2>

    <p>
        I am a Computer Science and Engineering student specializing in Cyber Security.
        I enjoy learning new technologies, building websites, and improving my
        programming skills to create innovative and secure software solutions.
    </p>

    <h2>Hobbies</h2>

    <ul>
        <li>Coding</li>
        <li>Learning Cyber Security</li>
        <li>Listening to Music</li>
    </ul>

    <div class="social-icons">
        <a href="#"><i class="fab fa-github"></i></a>
        <a href="#"><i class="fab fa-linkedin"></i></a>
        <a href="#"><i class="fab fa-instagram"></i></a>
    </div>

    <button>Contact Me</button>

</div>

</body>
</html>
```
#style.css:
```
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:linear-gradient(135deg,#4facfe,#00f2fe);
    display:flex;
    justify-content:center;
    align-items:center;
    min-height:100vh;
    padding:20px;
}

.card{
    background:#fff;
    width:360px;
    padding:30px;
    border-radius:20px;
    box-shadow:0 10px 30px rgba(0,0,0,0.2);
    text-align:center;
    transition:0.4s ease;
}

.card:hover{
    transform:translateY(-10px) scale(1.02);
}

.profile-img{
    width:150px;
    height:150px;
    border-radius:50%;
    object-fit:cover;
    border:5px solid #4facfe;
    margin-bottom:20px;
}

h1{
    color:#222;
    margin-bottom:10px;
}

h3{
    color:#666;
    font-weight:500;
    margin-bottom:20px;
}

h2{
    margin-top:15px;
    color:#333;
}

p{
    margin-top:10px;
    color:#555;
    line-height:1.6;
}

ul{
    list-style:disc;
    text-align:left;
    margin:15px auto;
    width:70%;
    color:#555;
}

li{
    margin:8px 0;
}

.social-icons{
    margin:20px 0;
}

.social-icons a{
    text-decoration:none;
    color:#4facfe;
    font-size:28px;
    margin:0 10px;
    transition:0.3s;
}

.social-icons a:hover{
    color:#0077b6;
    transform:scale(1.2);
}

button{
    background:#4facfe;
    color:white;
    border:none;
    padding:12px 35px;
    border-radius:30px;
    font-size:16px;
    cursor:pointer;
    transition:0.3s;
}

button:hover{
    background:#0077b6;
    transform:scale(1.05);
}

@media(max-width:480px){

.card{
    width:100%;
    padding:20px;
}

.profile-img{
    width:120px;
    height:120px;
}

h1{
    font-size:24px;
}

}
```
# Output:
<img width="1911" height="912" alt="image" src="https://github.com/user-attachments/assets/e8813264-a9e6-44e7-a88e-cadb25a224f1" />
