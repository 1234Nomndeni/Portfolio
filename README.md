<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA compactible">
    <meta name="viewpoint" content="width=de">
    <title>My Portfolio website</title>
    <link rel="stylesheet" href="mypage.css">
</head>
<body>
    <nav class="nav-bar">
        <h1><Nomndeni Nkosi></h1>
        <div class="nav-links">
            <a href="">About</a>
            <a href="">Home</a>
            <a href="Resume.html">Resume</a>
            <a href="./contactdetails.html">Contact</a><br>
        </div>
    </nav>
    <section class="hero">
        <div class="home-desc">
            <img width=100 marginleft="0" src="./Nom nom.html.jpg" alt="Nomndeni">
            <div class="home-content">
                <h1 class="naming"> Hello <img width="30" src="world.html.html" alt="">, my name is<span class="name-style"> Nomndeni Nkosi</h1><br>
                <p class="home-content"> Welcome to my website, which is intended to share my educational and programming adventures. To begin, Nomndeni is a nature conservationist by profession, having graduated from the University of Mpumalanga and Nelson Mandela University.I am currently doing my Bachelor of Science Honours in Environmental Management with the University of South Africa. I'm getting into programming to learn how to use technology to solve and address environmental problems. The ultimate goal is to create environmental websites to raise awareness and create website applications to monitor and protect our biodiversity.`</p>
                <a class= "homee" href="Contact me.html">
                    <button>Contact me</button>
            </a>   
        </div>
    </div>
    </section>
</body>
</html>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.nav-bar{
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: rgb(114, 218, 119);
    color: black;
    padding: 2rem 4rem;
    opacity: 1;
}
.nav-links{
    display: flex;
    gap: 27px;;
}
.nav-links > a {
    text-decoration: dotted;
    color: blue;
    font-size: 18px;
    cursor: pointer;
}
.hero{
    background-color: rgba(221, 218, 218, 0.637);
    min-height: 70vh;
}
.home-desc{
    display: flex;
    justify-content: space-between;
    width: 80%;
    margin: auto;
    padding-top:8rem;
    color: black;
}
.home-desc > img{
    width: 300px;
    height: 400px;
}
.home-content{
    width: 80%;  
    margin-left: 3rem; 
}
.home-content> h1{
    font-size: 3rem;
    margin-bottom: 3rem;
    width: 100%;
}
.name-style {
    color: rgb(46, 10, 253);
    font: bold;
}
.home-content> p{
    width: 80%;
    margin-bottom: 3rem;
    line-height: 30px;
    margin: evenly;
}
.home-content a > button:hover{
    background-color: blue;
    color: bisque;
    font font-weight: bold;
}
.home-content a > button{
    border-radius: 999px;
    border: 2px solid black;
    cursor: pointer;
    padding: 1rem 4rem;
}
.homee> a {
    background-color: blueviolet;
}
