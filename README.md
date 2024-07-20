<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sakshee Sawant - Software Engineer</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      display: flex;
    }
    .sidebar {
      width: 250px;
      background-color: #f4f4f4;
      height: 100vh;
      padding: 20px;
      box-shadow: 2px 0 5px rgba(0,0,0,0.1);
      position: fixed;
      top: 0;
      left: 0;
      overflow-y: auto;
    }
    .content {
      margin-left: 250px;
      padding: 20px;
    }
    .sidebar img {
      border-radius: 50%;
      width: 100%;
      height: auto;
      margin-bottom: 10px; /* Adjust spacing between image and name */
    }
    .sidebar .name {
      text-align: center;
      font-size: 1.2em;
      font-weight: bold;
      color: #333;
    }
    .sidebar a {
      display: block;
      padding: 10px 0;
      color: #333;
      text-decoration: none;
    }
    .sidebar a:hover {
      background-color: #ddd;
    }
    .section {
      margin-bottom: 20px;
    }
    .section h2 {
      margin-top: 0;
      color: #0077cc; /* Blue color for headings */
    }
    .social-icons {
      display: flex;
      justify-content: space-between;
      margin-top: 10px;
    }
    .social-icons a {
      display: inline-block;
      width: 30px;
      height: 30px;
      margin-right: 10px;
    }
  </style>
</head>
<body>
  <div class="sidebar">
    <div align="center">
      <img src="SAKSHEE.jpg" alt="Sakshee Sawant">
      <div class="name">Sakshee Sawant</div>
    </div>
    <a href="#about">About Me</a>
    <a href="#education">Education</a>
    <a href="#experience">Professional Experience</a>
    <a href="#projects">Projects</a>
    <a href="#skills">Skills</a>
    <a href="#contact">Contact</a>
    <div class="social-icons">
      <a href="mailto:sakshee.sawant@nyu.edu"><img src="email-icon.png" alt="Email"></a>
      <a href="https://www.linkedin.com/in/saksh12"><img src="linkedin-icon.png" alt="LinkedIn"></a>
      <a href="https://github.com/saksheesawant215"><img src="github-icon.png" alt="GitHub"></a>
    </div>
  </div>
  <div class="content">
    <section id="about">
      <h2>Hey there! 👋</h2>
      <p>I'm Sakshee, a passionate software engineer with a knack for turning complex data into meaningful insights and innovations. Originally from Mumbai, now navigating the vibrant tech scene in New York City while pursuing my Master's in Computer Engineering at NYU.</p>
    </section>

    <section id="education">
      <h2>Education</h2>
      <p><strong>New York University, NY</strong><br>Master’s in Computer Engineering (GPA: 3.6/4)<br>09/2023 – 05/2025</p>
      <p><em>Relevant Coursework:</em> Principles of Database Systems, Probability and Stochastic Processes, Machine Learning, Advanced Machine Learning, Deep Learning, Machine Learning for Cybersecurity, System Engineering</p>
      <p><strong>University of Mumbai, India</strong><br>Bachelor of Engineering in Computer Engineering (GPA: 9.47/10)<br>07/2018 – 05/2022</p>
      <p><em>Relevant Coursework:</em> Database Management System, Data Warehousing & Mining, Machine Learning, Software Engineering</p>
    </section>

    <section id="experience">
      <h2>Professional Experience</h2>
      <p><strong>Research Assistant, New York University</strong><br>02/2024 – Present<br>Contribute to research on pile bearing capacity and machine learning applications. Curate and preprocess large datasets, ensuring data quality, and assist in ML model development.</p>
      <p><strong>Data Engineering Associate, Accenture</strong><br>09/2022 – 08/2023<br>Optimized data transformation and loading using ETL Informatica PowerCenter, improving performance by 22%. Streamlined data loading processes using SQL Server Management Studio (SSMS) and Salesforce.</p>
      <p><strong>Machine Learning Intern, Juppiter AI Labs</strong><br>07/2022 – 09/2022<br>Developed an automated system for real estate agents using Deep Learning and Python, reducing manual effort by 45% and increasing productivity by 58%.</p>
      <p><strong>Backend Development Intern, Ifanow - Futurewise Technologies Pvt Ltd</strong><br>08/2021 – 11/2021<br>Created APIs for email categorization and AWS S3 multipart uploads, enhancing system efficiency. Improved data retrieval times by 30% through SQL database updates.</p>
      <p><strong>Software Engineer Intern, VESIT Renaissance Cell</strong><br>06/2021 – 08/2021<br>Developed "M-Vahitaram," an Android app for real-time crowd density information with a Firebase backend. Achieved 93% accuracy in crowd density prediction, leading to a publication in Springer's Proceedings of Emerging Trends and Technologies on Intelligent Systems.</p>
    </section>

    <section id="projects">
      <h2>Projects That Fuel My Passion</h2>
      <p><strong>Nirbhay Naari - AI for Empowerment</strong><br>Creating safe havens with AI-powered tools for women's safety, blending tech with compassion. This project is close to my heart, aiming to make a tangible impact in society.</p>
      <p><strong>Entrepôt Optimisé—Smarter Warehousing</strong><br>Redefining warehouse efficiency with a dash of AI and optimization. Improving logistics and reducing environmental impact are core goals of this project.</p>
    </section>

    <section id="skills">
      <h2>My Toolbox 🛠️</h2>
      <p><strong>Languages:</strong> Java, Python, SQL, JavaScript</p>
      <p><strong>Technologies:</strong> AWS, Django, Salesforce, Informatica PowerCenter, Android Studio</p>
      <p><strong>Tools:</strong> SQL Server Management Studio (SSMS), Git, TensorFlow, Keras</p>
      <p><strong>Methodologies:</strong> Machine Learning, Deep Learning, Data Warehousing, ETL, API Development</p>
      <p>I'm passionate about staying ahead in technology trends and applying innovative solutions to real-world challenges.</p>
    </section>

    <section id="contact">
      <h2>Let's Connect!</h2>
      <p>Feel free to drop me an email or connect via LinkedIn. Whether it's discussing tech, collaborating on projects, or just swapping stories, I'm always up for a chat!</p>
      <div class="social-icons">
        <a href="mailto:sakshee.sawant@nyu.edu"><img src="email-icon.png" alt="Email"></a>
        <a href="https://www.linkedin.com/in/saksh12"><i class='fab fa-linkedin' style='font-size:24px'></i>></a>
        <a href="https://github.com/saksheesawant215"><i class='fab fa-github-square' style='font-size:24px'></i></a>
      </div>
    </section>
  </div>
</body>
</html>
