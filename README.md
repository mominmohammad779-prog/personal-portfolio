# personal-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
 
    <title> Mohammed Momin - Personal Portfolio</title>
 
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f4f6f8;
            color: #333;
        }
 
        header {
            background-color: #1f4e79;
            color: white;
            text-align: center;
            padding: 40px 20px;
        }
 
        header h1 {
            margin: 0;
            font-size: 40px;
        }
 
        header p {
            font-size: 18px;
        }
 
        nav {
            background-color: #17365d;
            text-align: center;
            padding: 15px;
            position: sticky;
            top: 0;
        }
 
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
 
        nav a:hover {
            color: #ffd966;
        }
 
        section {
            background-color: white;
            margin: 25px auto;
            padding: 30px;
            width: 85%;
            max-width: 1000px;
            border-radius: 10px;
            box-shadow: 0 2px 8px #ccc;
        }
 
        h2 {
            color: #1f4e79;
            border-bottom: 2px solid #1f4e79;
            padding-bottom: 8px;
        }
 
        .profile {
            text-align: center;
        }
 
        .profile img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 4px solid #1f4e79;
            object-fit: cover;
        }
 
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 15px;
        }
 
        th, td {
            border: 1px solid #999;
            padding: 12px;
            text-align: center;
        }
 
        th {
            background-color: #1f4e79;
            color: white;
        }
 
        ul {
            line-height: 2;
        }
 
        .skills {
            display: flex;
            gap: 50px;
            flex-wrap: wrap;
        }
 
        .skills div {
            flex: 1;
            min-width: 250px;
        }
 
        .resume-button {
            display: inline-block;
            background-color: #1f4e79;
            color: white;
            padding: 12px 20px;
            text-decoration: none;
            border-radius: 5px;
        }
 
        .resume-button:hover {
            background-color: #17365d;
        }
 
        iframe {
            width: 100%;
            height: 400px;
            border: none;
            border-radius: 8px;
        }
 
        form {
            display: flex;
            flex-direction: column;
        }
 
        label {
            margin-top: 10px;
            font-weight: bold;
        }
 
        input, textarea {
            padding: 12px;
            margin-top: 5px;
            border: 1px solid #aaa;
            border-radius: 5px;
            font-size: 15px;
        }
 
        textarea {
            height: 120px;
        }
 
        button {
            margin-top: 20px;
            padding: 12px;
            background-color: #1f4e79;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
        }
 
        button:hover {
            background-color: #17365d;
        }
 
        footer {
            background-color: #17365d;
            color: white;
            text-align: center;
            padding: 25px;
            margin-top: 30px;
        }
 
        footer a {
            color: #ffd966;
            margin: 10px;
        }
    </style>
</head>
 
<body>
 
   
    <header>
        <h1>Mohammed Momin</h1>
        <p>Student | Aspiring IT Professional</p>
        <p>“Learning today, building a better tomorrow.”</p>
    </header>
 

   
    <nav>
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#certifications">Certifications</a>
        <a href="#projects">Projects</a>
        <a href="#resume">Resume</a>
        <a href="#video">Video</a>
        <a href="#contact">Contact</a>
    </nav>
 

       <section id="about">
        <h2>About Me</h2>
 
        <div class="profile">
            <img src="C:\users\dell\Pictures\Screenshots\Screenshot 2026-08-31 220936.png" alt="Profile Photo">
 
            <h3>Hello! I am Mohammed Momin</h3>
 
            <p>
                I am a motivated and enthusiastic student interested in
                technology, web development, and computer applications.
                I enjoy learning new skills and applying my knowledge
                through practical projects.
            </p>
 
            <h3>Career Objective</h3>
 
            <p>
                My career objective is to develop a successful career in
                the IT field by improving my technical knowledge, gaining
                practical experience, and contributing positively to an
                organization.
            </p>
 
            <h3>Hobbies & Interests</h3>
 
            <p>
                My hobbies and interests include learning new technologies,
                browsing the internet, listening to music, travelling,
                and exploring new ideas.
            </p>
        </div>
    </section>
 

    <section id="education">
        <h2>Education</h2>
 
        <table>
            <tr>
                <th>Qualification</th>
                <th>Institution</th>
                <th>Year</th>
                <th>Percentage / CGPA</th>
            </tr>
 
            <tr>
                <td>SSLC</td>
                <td>Lourdes boys high school</td>
                <td>Completed</td>
                <td>76%</td>
            </tr>
 
            <tr>
                <td>PUC</td>
                <td>Science academy PU College</td>
                <td>Completed</td>
                <td>67%</td>
            </tr>
 
            <tr>
                <td>Degree</td>
                <td>Aditya Institute of Management Studies</td>
                <td>Pursuing / Completed</td>
                <td>6.9 CGPA</td>
            </tr>
        </table>
    </section>
 

    <section id="skills">
        <h2>Skills</h2>
 
        <div class="skills">
 
            <div>
                <h3>Technical Skills</h3>
                <ul>
                    <li>HTML5</li>
                    <li>CSS</li>
                    <li>JavaScript</li>
                    <li>Basic Python</li>
                    <li>Database Management</li>
                    <li>MS Office</li>
                </ul>
            </div>
 
            <div>
                <h3>Soft Skills</h3>
                <ul>
                    <li>Communication</li>
                    <li>Teamwork</li>
                    <li>Time Management</li>
                    <li>Problem Solving</li>
                    <li>Leadership</li>
                    <li>Quick Learning</li>
                </ul>
            </div>
 
        </div>
    </section>
 

   
    <section id="certifications">
        <h2>Certifications & Achievements</h2>
 
        <ul>
            <li>Completed basic HTML and CSS learning.</li>
            <li>Participated in academic and technical activities.</li>
            <li>Completed computer-related coursework.</li>
            <li>Developed academic projects using web technologies.</li>
            <li>Continuously learning new technical skills.</li>
        </ul>
    </section>
 

    <section id="projects">
        <h2>Projects</h2>
 
        <h3>Personal Portfolio Website</h3>
        <p>
            Created a single-page personal portfolio website using HTML5
            and CSS. The website contains information about my education,
            skills, projects, resume, and contact details.
        </p>
 
        <h3>Tourism Webpage</h3>
        <p>
            Created a webpage introducing tourist places using headings,
            paragraphs, images, links, lists, tables, figures, and iframe.
        </p>
    </section>
    <section id="resume">
        <h2>Resume</h2>
 
        <p>
            My resume contains information about my education, technical
            skills, soft skills, projects, achievements, and career
            objectives.
        </p>
        <a href="C:\users\dell\Pictures\Screenshots\Screenshot 2026-08-31 222309.png" target="_blank">
            View / Download Resume
        </a>
    </section>
 

    <section id="video">
        <h2>Educational Video</h2>
 
        <p>
            Here is an educational video about HTML for beginners:
        </p>
 
               <iframe
            src="https://www.youtube.com/embed/pQN-pnXPaVg"
            title="HTML Tutorial for Beginners"
            allowfullscreen>
        </iframe>
    </section>
 

    <section id="contact">
        <h2>Contact Me</h2>
 
        <form>
 
            <label for="name">Name:</label>
            <input type="text" id="name" name="name"
                   placeholder="Enter your name" required>
 
            <label for="email">Email:</label>
            <input type="email" id="email" name="email"
                   placeholder="Enter your email" required>
 
            <label for="phone">Phone:</label>
            <input type="tel" id="phone" name="phone"
                   placeholder="Enter your phone number">
 
            <label for="subject">Subject:</label>
            <input type="text" id="subject" name="subject"
                   placeholder="Enter subject">
 
            <label for="message">Message:</label>
            <textarea id="message" name="message"
                      placeholder="Enter your message"></textarea>
 
            <button type="submit">Submit</button>
 
        </form>
    </section>
 

    <footer>
 
        <p>
            <strong>Email:</strong>
            mohammedmomin1.5@email.com
        </p>
 
        <p>
            <strong>Phone:</strong>
            +91 XXXXX XXXXX
        </p>
 
        <p>
            <strong>Social Media:</strong>
            <a href="https://www.linkedin.com/" target="_blank">
                LinkedIn
            </a>
 
            <a href="https://www.instagram.com/" target="_blank">
                Instagram
            </a>
 
            <a href="https://github.com/" target="_blank">
                GitHub
            </a>
        </p>
 
        <p>
            &copy; 2026 Mohammed Momin. All Rights Reserved.
        </p>
 
    </footer>
 
</body>
</html>
 