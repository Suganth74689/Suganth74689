<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Suganth | Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
    scroll-behavior:smooth;
}

body{
    background:#0f172a;
    color:#fff;
}

.navbar{
    position:fixed;
    top:0;
    width:100%;
    background:rgba(15,23,42,.9);
    backdrop-filter:blur(10px);
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 8%;
    z-index:1000;
}

.logo{
    font-size:28px;
    font-weight:700;
    color:#38bdf8;
}

.nav-links{
    display:flex;
    gap:25px;
}

.nav-links a{
    color:white;
    text-decoration:none;
    transition:.3s;
}

.nav-links a:hover{
    color:#38bdf8;
}

.hero{
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    flex-direction:column;
    text-align:center;
    padding:20px;
}

.hero h1{
    font-size:4rem;
    margin-bottom:10px;
}

.hero span{
    color:#38bdf8;
}

.hero p{
    max-width:700px;
    color:#cbd5e1;
    margin-bottom:30px;
}

.btn{
    display:inline-block;
    padding:12px 28px;
    background:#38bdf8;
    color:#fff;
    border-radius:30px;
    text-decoration:none;
    transition:.3s;
}

.btn:hover{
    transform:translateY(-5px);
}

section{
    padding:100px 10%;
}

.title{
    text-align:center;
    font-size:2.5rem;
    margin-bottom:50px;
    color:#38bdf8;
}

.about{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:40px;
    align-items:center;
}

.about-card{
    background:#1e293b;
    padding:30px;
    border-radius:15px;
}

.skills{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(150px,1fr));
    gap:20px;
}

.skill{
    background:#1e293b;
    padding:20px;
    text-align:center;
    border-radius:12px;
    transition:.3s;
}

.skill:hover{
    transform:translateY(-8px);
    background:#334155;
}

.projects{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:30px;
}

.project-card{
    background:#1e293b;
    padding:25px;
    border-radius:15px;
    transition:.3s;
}

.project-card:hover{
    transform:translateY(-10px);
}

.contact{
    text-align:center;
}

.footer{
    text-align:center;
    padding:30px;
    background:#020617;
    color:#94a3b8;
}

.typing{
    overflow:hidden;
    border-right:.15em solid #38bdf8;
    white-space:nowrap;
    animation:
        typing 4s steps(30,end),
        blink .75s step-end infinite;
}

@keyframes typing{
    from{width:0}
    to{width:100%}
}

@keyframes blink{
    50%{border-color:transparent}
}

@media(max-width:768px){

.about{
    grid-template-columns:1fr;
}

.hero h1{
    font-size:2.5rem;
}

.nav-links{
    gap:12px;
    font-size:14px;
}
}
</style>
</head>

<body>

<nav class="navbar">
    <div class="logo">SUGANTH</div>

    <div class="nav-links">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </div>
</nav>

<section class="hero" id="home">
    <h1>Hello, I'm <span>Suganth</span></h1>

    <h2 class="typing">
        Full Stack Developer | MERN Stack Developer
    </h2>

    <br>

    <p>
        Passionate software developer focused on building scalable web applications,
        real-time systems, and AI-powered solutions using modern technologies.
    </p>

    <a href="#about" class="btn">Explore More</a>
</section>

<section id="about">
    <h2 class="title">About Me</h2>

    <div class="about">
        <div class="about-card">
            <h3>Professional Summary</h3>
            <br>
            <p>
                Full Stack Developer specializing in MERN Stack development.
                Experienced in building modern web applications,
                real-time systems, and secure backend architectures.
            </p>
        </div>

        <div class="about-card">
            <h3>Career Objective</h3>
            <br>
            <p>
                To contribute to innovative software solutions,
                continuously improve my technical expertise,
                and create products that solve real-world problems.
            </p>
        </div>
    </div>
</section>

<section id="skills">
    <h2 class="title">Tech Stack</h2>

    <div class="skills">
        <div class="skill">HTML5</div>
        <div class="skill">CSS3</div>
        <div class="skill">JavaScript</div>
        <div class="skill">React.js</div>
        <div class="skill">Node.js</div>
        <div class="skill">Express.js</div>
        <div class="skill">MongoDB</div>
        <div class="skill">Git</div>
        <div class="skill">GitHub</div>
        <div class="skill">Java</div>
        <div class="skill">Python</div>
        <div class="skill">MySQL</div>
    </div>
</section>

<section id="projects">
    <h2 class="title">Projects</h2>

    <div class="projects">

        <div class="project-card">
            <h3>Apartment Visitor Log System</h3>
            <br>
            <p>
                MERN Stack application with JWT authentication,
                role-based access control, and real-time notifications.
            </p>
        </div>

        <div class="project-card">
            <h3>Future Projects</h3>
            <br>
            <p>
                AI-integrated applications, cloud-based systems,
                and enterprise-level web solutions.
            </p>
        </div>

    </div>
</section>

<section id="contact">
    <h2 class="title">Contact Me</h2>

    <div class="contact">
        <p>GitHub: github.com/Suganth74689</p>
        <br>
        <a href="https://github.com/Suganth74689" class="btn">
            Visit GitHub
        </a>
    </div>
</section>

<div class="footer">
    © 2026 Suganth | Full Stack Developer
</div>

</body>
</html>
