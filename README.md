# PORTPOLIO-WEBSITE:
Project 1:Personal Portfolio Website
• Technologies Used: HTML5, CSS3, JavaScript and Responsive Design
• Tool: Visual Studio Code
Description:
• Designed and developed a fully responsive personal portfolio to showcase projects, skills, and contact
information.
• Implemented clean UI/UX using modern web standards and optimized layout for mobile and desktop devices.
• Used JavaScript for interactive elements and smooth scrolling effects.

1.PORTPOLIO.HTML:
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Your Name | Front-End Developer</title>
  <link rel="stylesheet" href="portfolio.css"/>
  <link rel="stylesheet" href="career objective.html"/>
  <link rel="stylesheet" href="technical skills.html"/>
  <link rel="stylesheet" href="education.html"/>
  <link rel="stylesheet" href="projects.html"/>
  <link rel="stylesheet" href="languages.html"/>
  <link rel="stylesheet" href="key skills.html"/>
  
</head>
<body>
  <div>
    <div class="container">
      <h1>I'M BABY GOKULA</h1>
      <h2>Front-End Developer as a Fresher<h2><br>
        <p>My self Baby Gokula i'm a recent graduate with a strong passion for crafting responsive, user-friendly web interfaces</p><br><u></u>

      <nav>
        <ul>
          <a href="career objective.html"><u>CAREER OBJECTIVE</u></a><br>
          <a href="technical skills.html"><u>TECHNICAL SKILLS</u></a><br>
          <a href="education.html"><u>EDUCATION</u></a><br>
          <a href="projects.html"><u>PROJECTS</u></a><br>
          <a href="certifications.html"><u>CERTIFICATIONS</u></a><br>
          <a href="key skills.html"><u>KEY SKILLS</u></a><br>
          <a href="languages.html"><u>LANGUAGES</u></a>
        </ul>
    </nav>
      </div>
    </div>
  <script src="portfolio.js"></script>
</body>
</html>

2.PORTPOLIO.CSS:
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  body {
    font-family: 'Segoe UI', sans-serif;
    color: #0f0e0e;
    background:rgb(17, 16, 16);
    line-height: 1.6;
    text-align: center;
    padding: 2rem 0;
    content: var(center);
  }
  div{
    font-display: center;
    text-align: center;
  }
  h1{
    font-size: xx-large;
    color: orangered;
    font-weight: 5000;
  }
  h2{
    font-size: x-large;
    color: #10ac25;
    font-weight: 3000;
    
  }
  p{
    color: rgb(250, 11, 90);
  }
  
  .container {
    width: 90%;
    max-width: 1100px;
    margin: auto;
  }
  

  
  
  nav ul {
    list-style: none;
    margin-top: 1rem;
  }
  
  nav ul li {
    display: inline-block;
    margin: 0 15px;
  }
  
  nav a {
    text-decoration: none;
    color: #a50ad4;
    font-weight: bold;
  }
  
  .section {
    padding: 4rem 0;
    background:rgb(32, 31, 31);
  }
  .container1 h1{
    font-weight: 5000;
    color:rgb(7, 233, 233);
}
.container1 p{
    font-size: x-large;
    font-weight: 700;
    color: chocolate;

}
.container2 h1{
    font-weight: 5000;
    color:rgb(7, 233, 233);

}
.container2 p{
    font-size: x-large;
    font-weight: 700;
    color: chocolate;
}

    .container3 h1{
        font-weight: 5000;
        color:rgb(7, 233, 233);
    
    }
    .container3 p{
        font-size: x-large;
        font-weight: 700;
        color: chocolate;
    }

    .container4 h1{
        font-weight: 5000;
        color:rgb(7, 233, 233);
    }
        .container4 h3{
            font-weight: 5000;
            color:rgb(233, 7, 195);
    }
    .container4 p{
        font-size: x-large;
        font-weight: 700;
        color: chocolate;
    }
    .container4 h2{
        color: #10ac25;
    }


    .container5 h1{
        font-weight: 5000;
        color:rgb(7, 233, 233);
    
    }
    .container5 p{
        font-size: x-large;
        font-weight: 700;
        color: chocolate;
    }


    .container6 h1{
        font-weight: 5000;
        color:rgb(7, 233, 233);
    
    }
    .container6 p{
        font-size: x-large;
        font-weight: 700;
        color: chocolate;
    }



    .container7 h1{
        font-weight: 5000;
        color:rgb(7, 233, 233);
    
    }
    .container7 p{
        font-size: x-large;
        font-weight: 700;
        color: chocolate;
    }
    .container7 h2{
        color: #10ac25;
    }
  .skills-list {
    display: flex;
    flex-wrap: wrap;
    gap: 15px;
    list-style: none;
    padding: 0;
    font-size: 1.2rem;
    color: #141414;
    
  }
  
  .skills-list li {
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    padding: 10px 20px;
    border-radius: 5px;
  }
  
  .projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 20px;
  }
  
  .project-card {
    background: #fff;
    border: 1px solid #ddd;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    text-align: center;
  }
  
  .project-card img {
    width: 100%;
    height: auto;
  }
  
  form {
    max-width: 500px;
    margin: auto;
    display: flex;
    flex-direction: column;
  }
  
  form input, form textarea {
    margin-bottom: 1rem;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
  }
  
  form button {
    padding: 10px;
    background: #282c34;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
  }
  
  footer {
    text-align: center;
    padding: 2rem 0;
    background: #282c34;
    color: white;
  }

  3.PORTPOLIO.JS:
  document.getElementById('contactForm').addEventListener('submit', function(e) {
    e.preventDefault();
    alert("Thank you for reaching out! I'll get back to you soon.");
  });

  4.CAREER OBJECTIVE.HTML:
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="portfolio.css" />
    <link rel="stylesheet" href="portfolio.html" />
    <title>Document</title>
</head>
<body><section id="about" class="section">
    <div class="container1">
    
          <h1><u>CAREER OBJECTIVE</u></h1><br><br><br>
          <p>
          -->Motivated and self-taught front-end developer with a passion for creating interactive and visually appealing user
             interfaces.</p>
             <p>
        -->Looking for an entry-level position to apply my coding skills and grow as a professional in a challenging and
            collaborative environment.</p>
            </div></section>
            <script src="portfolio.js"></script>
    
</body>

</html>
5.TECHNICAL SKILLS:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="portfolio.css" />
    <link rel="stylesheet" href="portfolio.html" />
    <title>Document</title>
</head>
<body>
    <section id=" Technical skills" class="section">
        <div class="container2">
          <h1> <u>Technical Skills</u></h1>
          <ul class="skills-list">
            <h2>Languages: </h2><p>HTML5, CSS3, JavaScript (ES6+).</p><br>
            <h2>Frameworks:</h2> <p>React.js.</p><br>
            <h2>Tools: </h2><p>Git, Visual Studio Code.</p><br>
            <h2>Concepts: </h2><p>Responsive Design, API Integration, Basic UI/UX principles</p>
          </ul>
          </div></section>
          <script src="portfolio.js"></script>
    
</body>
</html>
6.EDUCATION.HTML:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="portfolio.css" />
    <link rel="stylesheet" href="portfolio.html" />
    <title>Document</title>
</head>
<body>
    <section id="Education" class="section">
        <div class="container3">
          <h1><u>Education</u></h1>
          <p>Chaitanya Bharathi Institute Of Technology</p>
          <p>Bachelor’s of technology(ECE)/CGPA:7.20/2019-2025</p><br>
    
          <p>A.P.S.W.R Junior College For Girls</p>
          <p>Intermediate/CGPA:9.04/2019-2017</p><br>
    
          <p>Z.P.High School</p>
          <p>S.S.C/CGPA:8.3/2017-2015</p><br>
          </div></section>
          <script src="portfolio.js"></script>
    
</body>
</html>

7.PROJECTS.HTML:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="portfolio.css" />
    <title>Document</title>
</head>
<body>
    <section id="Projects" class="section">
        <div class="container4">
          <h1><u>PROJECTS</u></h1>
          <h2>Project :</h2><h3>Personal Portfolio Website</h3>
          <h2>Technologies Used:</h2><h3>HTML5, CSS3, JavaScript and Responsive Design</h3>
          <h2>Tool:</h2><h3> Visual Studio Code</h3>
          <h2>Description</h2>
          <p>
            1.Designed and developed a fully responsive personal portfolio to showcase projects, skills, and contact
        information.<br>
        2.Implemented clean UI/UX using modern web standards and optimized layout for mobile and desktop devices.<br>
        3.Used JavaScript for interactive elements and smooth scrolling effects.<br>
      </p>
      <h2>Project 2:</h2><h3> To-Do List App</h3>
      <h2>Technologies Used:</h2><h3> HTML5, CSS3 and JavaScript</h3>
      <h2>Tool:<h2><h3> Visual Studio Code</h3>
      <h2>Description</h2>
      <p>
        1.Developed a user-friendly task management app to add, edit, delete, and mark tasks as completed<br>
        2.Implemented dynamic DOM manipulation using JavaScript to update tasks in real time<br>
        3.Designed a responsive UI for smooth usage on desktop and mobile devices.<br>
        4.Focused on clean code structure and user interactions.<br>
      </p>
      <h2>Project 3:</h2><h3>Weather App</h3>
      <h2>Technologies Used:<h2><h3> HTML5, CSS3, JavaScript and openWeatherMap API.</h3>
      <h2>Tool:<h2><h3> Visual Studio Code</h3>
      <h2>Description</h2>
      <p>
        1.Developed a responsive weather application that displays real-time weather data using the openWeatherMap
          API.<br>
        2.Implemented search functionality to display temperature, humidity, and weather conditions for any city.<br>
        3.Designed a clean, mobile-friendly UI using CSS for enhanced user experience.<br>
        4.Ensured error handling for invalid city names and API issues.<br>
      </p>
      </div>
      </section>
      <script src="portfolio.js"></script>
    
</body>
</html>

8.CERTIFICATION.HTML:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="portfolio.css" />
    <link rel="stylesheet" href="portfolio.html" />
    <title>Document</title>
</head>
<body>
    <section id="Certifications" class="section">
        <div class="container5">
          <h1><u>Certifications</u></h1>
          <p>1.Java Full Stack Development Certification-J’spiders Institution.</p>
          <p>2.Front-end Certification-J’spiders Institution.</p>
</div>
</section>
<script src="portfolio.js"></script>

    
</body>
</html>
9.KEY SKILLS.HTML:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="portfolio.css" />
    <link rel="stylesheet" href="portfolio.html" />
    <title>Document</title>
</head>
<body>
    <section id="Certifications" class="section">
        <div class="container6">
          <h1><u>KEY SKILLS</u></h1>
          <p>Communication skills and Collaboration</p>
          <P>Problem-Solving</P>
          <P>Attention to Detail</P>
          <P>Adaptability and Continuous Learning</P>
          <P>Time management</P>
          <P>User-Centric Thinking</P>
        </div>
</section>
<script src="portfolio.js"></script>
    
    
</body>
</html>
10.LANGUAGES.HTML:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="portfolio.html" />
    <link rel="stylesheet" href="portfolio.css" />
</head>
<body>
    <section id="Languages" class="section">
        <div class="container7">
          <h1><u>Languages<u></u></h1>
          <h2>Languages:</h2> <p>1.English (Professional Proficiency)</p>
          <p>2.Telugu (Native Speaker)</p>
</div>
</section>
<script src="portfolio.js"></script>
    
</body>
</html>


