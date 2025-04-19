# profile
portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title> 

    
    <link rel="icon" href="favicon.ico" type="image/x-icon">

    
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@200;400;600;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="astyle.css">


    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" />
</head>

<body>

<header>
    <nav>
        <div class="left">NIHAL,s PORTFOLIO</div>
        <div class="right">
            <ul> 
                <li>
                    <span class="material-symbols-outlined">home</span>
                    <a href="#home">Home</a>
                </li>
                <li>
                    <span class="material-symbols-outlined">star</span>
                    <a href="#projects">Projects</a>
                </li>
                <li>
                    <span class="material-symbols-outlined">monitor</span>
                    <a href="#skills">Skills</a>
                </li>
                <li>
                    <span class="material-symbols-outlined">contacts</span>
                    <a href="#contact">Contact</a>
                </li>
            </ul>
        </div>
    </nav>
</header>

<main>
    
    <section id="home" class="firstsection">
        <div class="leftsection">
            <h1>Hello! I AM <span class="blue">Nihal Ahirwar</span></h1>
            <div> I am a <span id="element">Engineer</span></div>
            <div> Engineer | Cybersecurity Student </div>
        </div>

        <div class="rightsection">
            <img src="profile2.jpg" alt="Profile Image of Nihal Ahirwar">
        </div>
    </section>

    <!-- Links Section -->
    <div style="text-align:center;">
        <a href="https://github.com/Nihal-1111" class="btn">GitHub</a>
        <a href="https://www.linkedin.com/in/nihal-ahirwar-074402304/" class="btn">LinkedIn</a>
        <a href="resume.pdf" download class="btn">Download Resume</a>
    </div>

    <hr>

    <section id="projects" class="secondsection">
        <h1>Past Experience</h1>
    
        <h2>Project 1 - Multi Calculator</h2>
        <p>The Calculator Website is a multi-functional web application developed using HTML, CSS, and JavaScript.</p>
        <ul>
            <li>Standard Calculator - Basic arithmetic operations</li>
            <li>Age Calculator - Calculate age based on birthdate</li>
            <li>Calorie Calculator - Determine daily calorie needs based on user input</li>
        </ul>
    
        <h2>Project 2 - Fit Buddy</h2>
        <p>Fit Buddy App is a fitness tracking and personal training application designed to help users stay fit by providing exercise routines and workout plans.</p>
        <ul>
            <li>Workout Tracker - Track daily workouts and progress</li>
            <li>Exercise Library - Access to a library of exercises</li>
            <li>User-Friendly Interface – Clean and intuitive design using XML</li>
        </ul>
    
        <h2>Project 3 - serve bhojya</h2>
        <p>serve bhojya a tiffin centre website for stop your foods hustle</p>
        <ul>
            <li>Interactive Map - Navigate through key city locations</li>
            <li>Attractions Section - Learn about popular tourist spots</li>
            <li>Responsive Design - Works smoothly on all devices</li>
        </ul>
    
        <div style="text-align: center;">
            <a href="https://github.com/YourUsername/bhopal-explore" class="btn" target="_blank">View Project</a>
        </div>
    </section>
    

    
    <section id="skills" class="thirdsection">
        <h1>Skills</h1>
        <div class="skills-container">
            <div class="skill">
                <span class="material-symbols-outlined">code</span>
                <h2>Programming</h2>
                <p>HTML, CSS, JavaScript, Python, C++</p>
            </div>
            <div class="skill">
                <span class="material-symbols-outlined"></span>
                <h2>Soft Skills</h2>
                <p>communication, leadership, problem solving</p>
            </div>
            <div class="skill">
                <span class="material-symbols-outlined">security</span>
                <h2>Cybersecurity</h2>
                <p>Network Security, Ethical Hacking, Penetration Testing</p>
            </div>
        </div>
    </section>  
</main>

<hr>



<footer>
    <section id="contact"></section>
    <p>© 2025 Nihal Ahirwar | All Rights Reserved</p>
    <div class="footer-links"><li>
        <a href="https://instagram.com/yourusername" target="_blank">Instagram</a></li>
       <li> <a href="mailto:nihalahirwar07@gmail.com">Email</a></li>
    </div>
</footer>

<!-- Typed.js Animation -->
<script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
<script>
    var typed = new Typed('#element', {
        strings: ['Programmer', 'Frontend Developer', 'Cybersecurity Enthusiast'],
        typeSpeed: 40,
    });
</script>

</body>
</html>
