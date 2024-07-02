# codsoft_1
HTML CODE FOR PORTFOLIO WEBSITE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="stylep.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<body>
    <header>
        <nav>
        <div class="navbar">
            <div class="navdiv">
                <img src="images/logo.png" class="logo">
                    <ul>
                        <li><a href="#about"> About</a></li>
                        <li><a href="#skill-img"> Skills</a></li>
                        <li><a href="#projects"> Projects</a></li>
                        <li><a href="#heading3"> Resume</a></li>
                        <li><a href="#contact"> Contact</a></li>
                    </ul>
             </div>
        </div>
        </nav>
        <div class="home-img">
            <img src="images/photo1.jpg">
        </div>
        <div class="header-txt">
            <h1>Hello, I'm <span> SALONI</span></h1>
            <p>Creating content to display my skill, passion, experience.</p>
            <p>Web Developer</p>
        </div>
    </header>
  <!--------about-------->  
  <section id="about">
    <div class="about-img">
        <img src="images/photo1.jpg">
    </div>
    <div class="about-txt">
        <h2>About <span>Me</span></h2>
        <h4>Web Developer</h4>
        <p>Self-motivated, Adaptable, and Reliable front end web developer with 2 years' experience driving website and mobile-first application development projects. Detailed-oriented and efficient WordPress developer skilled in building custom themes and templates, integrating plugins to support digital marketing efforts, and completing user experience(UX) copywriting tasks. Supportive team player with strong data analysis skills.</p>
        <a href="#" class="btn-box"> More About Me</a>
    </div>
  </section>
  <!---------skills---------->
  <img id="skill-img" src="images/Skill.jpg">
  <h1 class="sub-title">My <span>Skills</span></h1>
  <section id="skill">
    <div class="container1" id="Skills">
    
        <h1 class="heading1">Technical Skills</h1>
        
        <div class="Technical-bars">
            <div class="bar">
                <div class="info">
                    <span>HTML</span>
                </div>
            </div>
            <div class="bar">
                <div class="info">
                    <span>CSS</span>
                </div>
            </div>
            <div class="bar">
                <div class="info">
                    <span>JavaScript</span>
                </div>
            </div>
            <div class="bar">
                <div class="info">
                    <span>Python</span>
                </div>
            </div>
            <div class="bar">
                <div class="info">
                    <span>React</span>
                </div>
            </div>
        </div>
        <h1 class="heading2">Professional Skills</h1>
        <div class="Professional-bars">
            <div class="bar1">
                <div class="info">
                    <span>Creativity</span>
                </div>                
            </div>
            <div class="bar1">
                <div class="info">
                    <span>Communication</span>
                </div>
            </div>
            <div class="bar1">
                <div class="info">
                    <span>Problem Solving</span>
                </div>
            </div>
            <div class="bar1">
                <div class="info">
                    <span>Team Work</span>
                </div>
            </div>
            <div class="bar1">
                <div class="info">
                    <span>Time Mnagement</span>
                </div>
            </div>
        </div>
    </div>
    <a href="#" class="btn-box"> More About Me</a>
  </section>
<!------------projects-------------->
<section id="projects">
    <h2>Projects</h2>
    <div class="project">
        <img src="images/landingpage.jpg" alt="Landing Page">
        <div class="project-info">
            <h3>Landing Page </h3>
            <p>This is a brief description of Project 1. It covers the main features and technologies used.</p>
            <a href="#" target="_blank">View on GitHub</a>
        </div>
    </div>
    <div class="project">
        <img src="images/calc.jpg" alt="Calculator">
        <div class="project-info">
            <h3>Calculator</h3>
            <p>This is a brief description of Project 2. It covers the main features and technologies used.</p>
            <a href="#" target="_blank">View on GitHub</a>
        </div>
    </div>
    </section>
    <!-------------resume--------------->
    <h2 id="heading3">Resume</h2>
    <div class="resume">
        <header class="header">
            <h1>Saloni Prajapati</h1>
            <p>Web Developer</p>
            <p>Email: salonice15@gmail.com | Phone: 8980393631</p>
            <p>Website: www.salonice15.dev | LinkedIn: linkedin.com/in/Saloni Prajapati</p>
        </header>
        
        <section id="section">
            <h2>Skills</h2>
            <ul>
                <li>HTML & CSS</li>
                <li>JavaScript</li>
                <li>React.js</li>
                <li>Node.js</li>
                <li>Responsive Design</li>
            </ul>
        </section>
        
        <section class="section">
            <h2>Experience</h2>
            <div class="job">
                <h3>Web Developer Intern</h3>
                <p>CodSoft, Jun 2024 - July 2024</p>
                <ul>
                    <li>Assisted in the development of potfolio websites using HTML and CSS.</li>
                    <li>Assisted in the development of Landing Page using HTML and CSS.</li>
                    <li>Assisted in the development of Calculator using HTML, CSS, and JavaScript.</li>
                </ul>
            </div>
        </section>
        
        <section class="section">
            <h2>Education</h2>
            <div class="education">
                <h3>Bachlelor of Engineering in Computer Engineering</h3>
                <p>Gujarat Power Engineering and Research Institute, 2021 - 2025</p>
            </div>
        </section>
        </div>
        <!---------contact--------->
        <section id="contact">
            <div class="content">
                <h2>Contact Me</h2>
                <p>I would love to hear from you!</p>
            </div>
            
                <div class="contactForm">
                    <form>
                        <h2>Send Message</h2>
                        <div class="inputBox">
                            <span>Full Name</span>
                            <input type="text" name="" required="required">                           
                        </div>
                        <div class="inputBox">
                            <span>Email</span>
                            <input type="text" name="" required="required">
                        </div>
                        <div class="inputBox">
                            <span>Type Your Message...</span>
                            <textarea required="required"></textarea>                          
                        </div>
                        <div class="inputBox">
                            <input type="submit" name="" value="Send">
                        </div>
                    </form>
                </div>
            </div>
        </section>
    <footer>
        <div class="container2">
            <div class="footer-content">
                <h3>Contact Me</h3>
                <p>Email:salonice15@gmail.com</p>
                <p>phone:8980393631</p>
                <p>Mehsana,Gujarat,India</p>
            </div>
            <div class="footer-content">
                <h3>Follow Me</h3>
                <ul class="social-icons">
                <li><a href=""><i class="fa fa-facebook"></i></a></li>
                <li><a href=""><i class="fa fa-twitter"></i></a></li>
                <li><a href=""><i class="fa fa-instagram"></i></a></li>
                <li><a href=""><i class="fa fa-linkedin"></i></a></li>
                </ul>
            </div>
        </div>
        <div class="bottom-bar">
            <p> &copy; All rights reserved.</p>
        </div>
    </footer>
</body>
</html>

CSS CODE :

*{
    font-family: Arial;
    border: border-box;
    text-decoration: none;
}
body{
    background: #080808;
    color: #fff;
}
.navbar{
    height: 60px;
    background-color: #080808;
    color: aliceblue;
    padding-left: 20px;
    padding-right: 20px;
    animation: slideTop 0.5s ease forwards;
}
.navdiv{
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.port a{

    font-weight: bolder;
    color: aquamarine;
    padding-top: 15px;
    padding-bottom: 20px;
    padding-left: 20px;
    font-size: 20px;
}
li{
    display: inline-block;
    list-style: none;
}
li a{
    color: aliceblue;
    font-size: 15px;
    font-weight: bold;
    margin-right: 25px;
    padding-top: 20px;
}
li a:hover{
    color: rgb(60, 171, 212);
}
.logo{
    width: 100px;
    height: 40px;
    
}
.home-img img{
    float: right;
    height: 300px;
    width: 300px;
    border-radius: 50%;
    border: 10px  solid rgb(60, 171, 212);
    margin-right: 200px;
    margin-top: 150px;
}
.header-txt{
    margin-top: 20%;
    font-size: 60px;
    color:aliceblue ;
    animation: slideLeft 0.5s ease forwards;
    animation-delay: .7s;
}
.header-txt{
    font-size: 30px;
}
.header-txt h1 span{
    color: rgb(60, 171, 212);
}
#about{
    display: grid;
    grid-template-columns: repeat(2,1fr);
    align-items: center;
    gap: 1.5rem;
}
.about-img{
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;  
}
.about-img img{
    height: 300px;
    width: 300px;
    border-radius: 50%;
    border: 10px solid rgb(60, 171, 212) ;
}
.about-txt h2{
    font-size: 60px;
    animation: slideLeft 0.5s ease forwards;
    animation-delay: .7s;
}
.about-txt h2 span{
    color:rgb(60, 171, 212);
}
.about-txt h4{
    font-size: 29px;
    font-weight: 600;
    color: #fff;
    line-height: 1.7;
    margin: 15px 0 30px;
    animation: slideRight 0.5s ease forwards;
    animation-delay: .7s;
}
.about-txt p{
    color:aliceblue;
    font-size: 20px;
    line-height: 1.4;
    margin-bottom: 4rem;
    animation: slideBottom 0.5s ease forwards;
    animation-delay: .7s;
}
.about-txt a {
    color: rgb(60, 171, 212);
    animation: slideTop 0.5s ease forwards;
    animation-delay: .7s;
}
#skill-img{
    float: right;
    width: 50%;
    padding-top: 150px;
    margin-right: 100px;
}
#skill{
    display: flex;
    flex-wrap: wrap;
}
.container1{
    width: 600px;
    height: 500px;
    padding: 75px 90px;
    margin-left: 120px;
}
h1 span{
    color:rgb(60, 171, 212) ;
    align-items: center;
}
.sub-title{
    margin-left: 200px;
    margin-bottom: 0;
    font-size: 60px;
    animation: slideLeft 0.5s ease forwards;
    animation-delay: .7s;
}
.heading1{
    color: rgb(60, 171, 212);
    text-align: left;
    text-decoration: underline;
    text-underline-offset: 10px;
    text-decoration-thickness: 5px;
    margin-bottom: 50px;
    animation: slideBottom 0.5s ease forwards;
    animation-delay: .7s;
}
.bar{
    font-size: 23px;
}
.Technical-bars{
    margin-top: 40px 0;
}
.Technical-bars .bar:first-child{
    margin-top: 0;
}
.Technical-bars .bar:last-child{
    margin-bottom: 0;
}
.Technical-bars .bar .info{
    margin-bottom: 5px;
    animation: slideRight 0.5s ease forwards;
    animation-delay: .7s;
}
.Technical-bars .bar .info span{
    font-size: 17px;
    font-weight: 500;
    animation: showText 0.5s 1s linear forwards;

}
.heading2{
    color: rgb(60, 171, 212);
    text-align: left;
    text-decoration: underline;
    text-underline-offset: 10px;
    text-decoration-thickness: 5px;
    margin-bottom: 50px;
    animation: slideBottom 0.5s ease forwards;
    animation-delay: .7s;
}
.bar1{
    font-size: 23px;
}
.Professional-bars{
    margin-top: 40px 0;
}
.Professional-bars .bar1:first-child{
    margin-top: 0;
}
.Professional-bars .bar1:last-child{
    margin-bottom: 0;
}
.Professional-bars .bar1 .info{
    margin-bottom: 5px;
    animation: slideRight 1s ease forwards;
    animation-delay: .7s;
}
.Professional-bars .bar1 .info span{
    font-size: 17px;
    font-weight: 500;
}
#skill a {
    color: rgb(60, 171, 212);
    margin-left: 200px;
    animation: slideTop 0.5s ease forwards;
    animation-delay: .7s;
}
#projects {
    padding: 50px;
    background-color: #080808;
}

#projects h2 {
    text-align: center;
    margin-bottom: 40px;
    font-size: 60px;
    color:rgb(60, 171, 212);
}

.project {
    display: flex;
    align-items: center;
    background-color: #080808;
    margin-bottom: 20px;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.project img {
    max-width: 150px;
    margin-right: 20px;
    border-radius: 8px;
}

.project-info {
    flex-grow: 1;
}

.project-info h3 {
    margin: 0 0 10px;
    font-size: 1.5em;
    color:#fff;
}

.project-info p {
    margin: 0 0 10px;
    color:whitesmoke;
}

.project-info a {
    text-decoration: none;
    color: rgb(60, 171, 212);
    font-weight: bold;
}

.project-info a:hover {
    text-decoration: underline;
}
.resume {
    max-width: 800px;
    margin: 20px auto;
    background: #fff;
    padding: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}
#heading3{
    color:  rgb(60, 171, 212);
    text-align: center;
    margin-bottom: 40px;
    font-size: 60px;
}

.header {
    text-align: center;
    border-bottom: 2px solid rgb(60, 171, 212);
    padding-bottom: 10px;
}

.header h1 {
    margin: 0;
    font-size: 2em;
    color: #333;
}

.header p {
    margin: 5px 0;
    color: #666;
}

#section {
    margin-top: 20px;
}

#section h2 {
    margin-bottom: 10px;
    color: rgb(60, 171, 212);
    border-bottom: 1px solid #ddd;
    padding-bottom: 5px;
}

ul {
    list-style-type: none;
    padding: 0;
}

ul li {
    background: url('https://i.imgur.com/eAAG7Es.png') no-repeat left center;
    background-size: 1em;
    padding-left: 20px;
    margin-bottom: 5px;
    color: #333;
}

.job, .education {
    margin-bottom: 20px;
}

.job h3, .education h3 {
    margin: 0;
    font-size: 1.2em;
    color: #333;
}

.job p, .education p {
    margin: 5px 0;
    color: #666;
}
#contact{
    position: relative;
    min-height: 100vh;
    padding: 50px 100px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}
#contact .content{
    max-width: 800px;
    text-align: center;

}
#contact .content h2{
    color: rgb(60, 171, 212);
    font-size: 60px;
}
#contact .content p{
    color: #fff;
    font-weight: 300;
    font-size: 30px;
}
.contactForm{
    width: 40%;
    padding: 40px;
    background: #fff;
}
.contactForm h2{
    font-size: 30px;
    color: #333;
    font-weight: 500;
}
.contactForm .inputBox{
    position: relative;
    width: 100%;
    margin-top: 10px;
}
.contactForm .inputBox input,
.contactForm .inputBox textarea
{
    width: 100%;
    padding: 5px;
    font-size: 16px;
    margin: 10px 0;
    border: none;
    border-bottom: 2px solid #333;
    outline: none;
    resize: none;
}
.contactForm .inputBox span{
    position: absolute;
    left: 0;

    pointer-events: none;
    color: #666;
}
.contactForm .inputBox input[type="submit"]{
    width: 100px;
    background:rgb(60, 171, 212) ;
    color: #fff;
    border: none;
}
footer{
    padding-top: 50px;
    background: grey;
}
.container2{
    width: 1140px;
    margin: auto;
    display: flex;
    justify-content: center;
}
.footer-content{
    width: 33.3%;
    color: #fff;
}
.footer-content h3{
    font-size: 29px;
    margin-bottom: 15px;
    text-align: center;
}
.footer-content p{
    width: 190px;
    margin: auto;
    padding: 7px;
}
.social-icons{
    text-align: center;
    padding: 0;
}
.social-icons li{
    display: inline-block;
    text-align: center;
    font-size: 5px;
}
a{
    text-decoration: none;
}
a:hover{
    color: rgb(60, 171, 212);
}
.social-icons i:hover{
    color: rgb(60, 171, 212);
}
.bottom-bar{
    background: rgb(60, 171, 212);
    text-align: center;
    padding: 10px 0;
    margin-top: 50px;
}
.bottom-bar p{
    color: #fff;
    margin: 0;
    font-size: 16px;
    padding: 7px;
}



@keyframes slideRight{
    0%{
        transform: translateX(-100px);
        opacity: 0;
    }
    100%{
        transform: translateX(0px);
        opacity: 1;
    }
}
@keyframes slideLeft{
    0%{
        transform: translateX(100px);
        opacity: 0;
    }
    100%{
        transform: translateX(0px);
        opacity: 1;
    }
}
@keyframes slideTop{
    0%{
        transform: translateY(100px);
        opacity: 0;
    }
    100%{
        transform: translateY(0px);
        opacity: 1;
    }
}
@keyframes slideBottom{
    0%{
        transform: translateY(100px);
        opacity: 0;
    }
    100%{
        transform: translateY(0px);
        opacity: 1;
    }
}
