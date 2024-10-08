<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Curriculum Vitae</title>
    <meta name="description" content="Dolly Mudau's Curriculum Vitae - A full stack developer and freelancer.">
    <meta name="keywords" content="Dolly Mudau, CV, Curriculum Vitae, Full Stack Developer, Freelancer">
    <meta name="author" content="Dolly Mudau">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            overflow-x: hidden; /* Prevent horizontal overflow */
        }
        header {
            background: #003366; /* Dark Blue */
            color: #ffffff;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav a {
            color: #ffffff;
            margin: 0 15px;
            text-decoration: none;
        }
        section {
            padding: 20px;
            margin: 10px;
            background: #ffffff;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .pdf-button {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background: #003366;
            color: #ffffff;
            text-decoration: none;
            border-radius: 5px;
        }
        .cover {
            text-align: center;
            padding: 50px;
            background: #003366; /* Dark Blue */
            color: #ffffff;
        }
        .cover img {
            max-width: 200px;
            border-radius: 50%;
        }
        .info-list {
            list-style-type: none;
            padding: 0;
        }
        form input, form textarea, form button {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        form button {
            background-color: #003366; /* Dark Blue */
            color: #ffffff;
            border: none;
        }
        form button:hover {
            background-color: #005599; /* Lighter Blue */
        }
        .hire-me {
            text-align: center;
            font-size: 24px;
            font-weight: bold;
            color: #003366; /* Dark Blue */
            margin: 20px 0;
        }
        #projects, #portfolio {
            background: #e0e0e0;
        }
        #projects h2, #portfolio h2 {
            color: #003366; /* Dark Blue */
        }
        /* Responsive Design */
        @media (max-width: 768px) {
            section {
                margin: 5px;
                padding: 15px;
            }
            header h1 {
                font-size: 24px;
            }
            nav a {
                margin: 0 10px;
            }
        }
        /* Custom Cursor */
        body {
            cursor: url('https://example.com/custom-cursor.png'), auto; /* Replace with your custom cursor URL */
        }
        /* Loading Animation */
        #loading {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(255, 255, 255, 0.8);
            display: flex;
            align-items: center;
            justify-content: center;
            z-index: 9999;
        }
        .loader {
            border: 5px solid #003366; /* Dark Blue */
            border-top: 5px solid #ffffff; /* White */
            border-radius: 50%;
            width: 50px;
            height: 50px;
            animation: spin 1s linear infinite;
        }
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        /* Contact Section */
        .contact-info {
            background: #e0f7fa; /* Light Cyan */
            padding: 15px;
            border-radius: 5px;
        }
        .contact-info a {
            color: #006064; /* Dark Cyan */
            text-decoration: none;
        }
        .contact-info a:hover {
            text-decoration: underline;
        }
        /* Scroll to Top Arrow */
        .scroll-to-top {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background: #003366; /* Dark Blue */
            color: #ffffff;
            border: none;
            border-radius: 5px;
            padding: 10px;
            cursor: pointer;
            display: none; /* Hidden by default */
        }
        .scroll-to-top:hover {
            background-color: #005599; /* Lighter Blue */
        }
    </style>
</head>
<body>

<div id="loading">
    <div class="loader"></div>
</div>

<header>
    <h1>My Curriculum Vitae</h1>
    <nav>
        <a href="#home" id="home-link">Home</a>
        <a href="#education">Education</a>
        <a href="#work-experience">Work Experience</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#" id="download-button">Download CV</a>
    </nav>
</header>

<section class="cover animate__animated animate__fadeIn" id="home">
    <h2>Welcome to My CV</h2>
    <img src="IMG_20231207_094959.jpg"  alt="Dolly Mudau"> <!-- Replace with your actual image URL -->
    <p>I'm Dolly Mudau. A full Stack Developer and Freelancer.</p>
</section>

<section class="hire-me animate__animated animate__fadeIn" id="hire-me">
    <h2>HIRE ME!</h2>
</section>

<section class="animate__animated animate__fadeIn" id="education">
    <h2>Education</h2>
    <p>I am a first-year Computer Science student passionate about technology and eager to learn and grow in the field. I have a strong interest in programming, problem-solving, and exploring various technologies like Python, JavaScript, and HTML. As I build a solid foundation in computer science, I am excited to apply my knowledge to real-world projects and continue developing my skills in software development and coding.</p>
    <p>I am particularly interested in areas such as web development, data structures, and algorithms, and I'm always looking for opportunities to expand my knowledge through hands-on projects and collaboration. I enjoy tackling challenges and finding innovative solutions, and I am dedicated to improving my technical skills while staying up-to-date with the latest advancements in the tech industry. My goal is to gain practical experience and contribute to impactful projects as I progress in my studies.</p>
    <h3>Skills</h3>
    <ul class="info-list">
        <li>Design: 80%</li>
        <li>HTML: 99%</li>
        <li>CSS: 80%</li>
        <li>Bootstrap: 75%</li>
        <li>JavaScript: 70%</li>
    </ul>
</section>

<section class="animate__animated animate__fadeIn" id="work-experience">
    <h2>Work Experience</h2>
    
<p>Systems Administrator | ABC Corporation
June 2020 – April 2022
Administered and monitored company-wide computer systems, ensuring 99% uptime.
Implemented security protocols, performed regular system backups, and maintained firewall configurations.
Diagnosed and resolved technical issues, minimizing system downtime and increasing productivity.
Led software deployment projects, including testing, installation, and troubleshooting across various platforms.
Managed user accounts and permissions in Active Directory, ensuring proper access control.
If this doesn't align with your experience, feel free to share specific roles or responsibilities, and I can help tailor it further.</p>
</section>

<section class="animate__animated animate__fadeIn" id="skills">
    <h2>Skills</h2>
    <p>In my latest work as a developer, I focused on building a full-stack web application that tracks and categorizes expenses. The project involved developing both the front-end and back-end using a combination of HTML, CSS, and JavaScript for the user interface, along with Node.js and SQL for server-side operations and database management. I implemented user authentication to ensure secure login and registration features, allowing users to manage their personal finances effectively.</p>
</section>

<section class="animate__animated animate__fadeIn" id="projects">
    <h2>Projects</h2>
    <ul class="info-list">
        <li><strong>Expense Tracker:</strong> A web application for tracking personal expenses with user authentication.</li>
        <li><strong>Portfolio Website:</strong> A personal portfolio site showcasing my projects and skills.</li>
        <li><strong>To-Do List App:</strong> A simple app for managing tasks and deadlines.</li>
        <li><strong>Blog Platform:</strong> A blogging platform where users can write and share articles.</li>
    </ul>
</section>

<section class="animate__animated animate__fadeIn" id="portfolio">
    <h2>Portfolio</h2>
    <ul class="info-list">
        <li><strong><a href="#" target="_blank">Project 1</a>:</strong> A web application that allows users to track their expenses.</li>
        <li><strong><a href="#" target="_blank">Project 2</a>:</strong> A personal portfolio site showcasing my skills.</li>
        <li><strong><a href="#" target="_blank">Project 3</a>:</strong> A simple To-Do list app with a user-friendly interface for managing tasks.</li>
        <li><strong><a href="#" target="_blank">Project 4</a>:</strong> A blogging platform where users can share their thoughts and articles with a user-friendly interface.</li>
    </ul>
</section>

<section id="contact" class="animate__animated animate__fadeIn">
    <h2>Contact Us</h2>
    <form id="contact-form">
        <input type="text" id="contact-name" placeholder="Your Name" required>
        <input type="email" id="contact-email" placeholder="Your Email" required>
        <textarea id="contact-message" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
    </form>
    <div class="contact-info">
        <p>Location: Polokwane</p>
        <p>Email: <a href="mailto:dollymudau214@gmail.com">dollymudau214@gmail.com</a></p>
        <p>Phone: <a href="https://wa.me/27678063558">0768063558</a></p>
    </div>
    <div class="map-container">
        <iframe 
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3225.511370379116!2d30.039292415042197!3d-23.908446084646848!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1e5e6a43c5cdbf91%3A0x6d6a97df2f918485!2sPolokwane%20International%20Airport!5e0!3m2!1sen!2sza!4v1696745702055!5m2!1sen!2sza" 
            width="100%" 
            height="450" 
            style="border:0;" 
            allowfullscreen="" 
            loading="lazy"></iframe>
    </div>
</section>

<section class="animate__animated animate__fadeIn">
    <h2>Having Questions?</h2>
    <p>If you have any questions or need further information, feel free to reach out!</p>
</section>

<section class="contact-info" style="background: #e0f2f1; padding: 15px; border-radius: 5px;">
    <h2>Contact Me</h2>
    <p>Also, you can reach out to me via:</p>
    <p>Facebook: <a href="https://facebook.com/your-profile" target="_blank">Your Facebook Profile</a></p>
    <p>WhatsApp: <a href="https://wa.me/27678063558">Chat on WhatsApp</a></p>
</section>

<footer>
    <p>Contact: <a href="mailto:dollymudau214@gmail.com">dollymudau214@gmail.com</a> | Phone: <a href="https://wa.me/27678063558">0768063558</a></p>
    <p>Location: Polokwane</p>
    <p>© 2024 DOLLY MUDAU</p>
</footer>

<!-- Scroll to Top Button -->
<button class="scroll-to-top" id="scroll-to-top">↑</button>

<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
<script>
    // Hide loading animation after the page has fully loaded
    window.onload = function() {
        document.getElementById('loading').style.display = 'none';
    };

    const { jsPDF } = window.jspdf;

    // PDF Download
    document.getElementById('download-button').addEventListener('click', function(event) {
        event.preventDefault();
        const doc = new jsPDF();

        // Welcome Message
        doc.setFontSize(20);
        doc.text("Welcome to My CV", 10, 10);
        doc.setFontSize(12);

        // Add Personal Information to the PDF
        doc.text("Personal Information:", 10, 20);
        doc.text("I'm Dolly Mudau. A full Stack Developer and Freelancer.", 10, 30);

        // Add Education to the PDF
        doc.text("Education:", 10, 40);
        doc.text("I am a first-year Computer Science student passionate about technology...", 10, 50); // Trimmed for brevity
        doc.text("Skills: Design 80%, HTML 99%, CSS 80%, Bootstrap 75%, JavaScript 70%", 10, 80);

        // Add Work Experience to the PDF
        doc.text("Work Experience:", 10, 90);
        doc.text("NO EXPERIENCE", 10, 100);

        // Add Skills to the PDF
        doc.text("Skills:", 10, 110);
        doc.text("In my latest work as a developer...", 10, 120); // Trimmed for brevity

        // Add Projects to the PDF
        doc.text("Projects:", 10, 130);
        doc.text("1. Expense Tracker", 10, 140);
        doc.text("2. Portfolio Website", 10, 150);
        doc.text("3. To-Do List App", 10, 160);
        doc.text("4. Blog Platform", 10, 170);

        // Add Portfolio to the PDF
        doc.text("Portfolio:", 10, 180);
        doc.text("1. Project 1: A web application that allows users to track their expenses.", 10, 190);
        doc.text("2. Project 2: A personal portfolio site showcasing my skills.", 10, 200);
        doc.text("3. Project 3: A simple To-Do list app.", 10, 210);
        doc.text("4. Project 4: A blogging platform for sharing articles.", 10, 220);

        // Save the PDF
        doc.save("my_cv.pdf");
    });

    // Scroll to Top Functionality
    const scrollToTopButton = document.getElementById('scroll-to-top');
    scrollToTopButton.addEventListener('click', function() {
        window.scrollTo({ top: 0, behavior: 'smooth' });
    });

    // Show/Hide Scroll to Top Button
    window.onscroll = function() {
        if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
            scrollToTopButton.style.display = 'block';
        } else {
            scrollToTopButton.style.display = 'none';
        }
    };
</script>

</body>
</html>
