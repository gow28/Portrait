
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Portfolio of Naga Gowthami Thanubuddu - Software Developer and Machine Learning Engineer.">
    <title>Naga Gowthami | Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.7;
            color: #333;
            background: #f4f6fa;
        }

        nav {
            background: #101827;
            padding: 15px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        nav h2 {
            color: white;
            font-size: 21px;
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 25px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-size: 14px;
        }

        nav a:hover {
            color: #60a5fa;
        }

        .hero {
            min-height: 380px;
            background:
                linear-gradient(rgba(8, 18, 35, 0.78),
                rgba(8, 18, 35, 0.85)),
                url("https://thumbs.dreamstime.com/b/data-science-deep-learning-artificial-intelligence-analysis-internet-modern-technology-concept-130068639.jpg")
                center/cover;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            padding: 40px 20px;
        }

        .hero h1 {
            font-size: 42px;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 19px;
            color: #dbeafe;
        }

        .hero-links {
            margin-top: 25px;
        }

        .hero-links a {
            display: inline-block;
            margin: 6px;
            padding: 10px 22px;
            border-radius: 5px;
            background: #2563eb;
            color: white;
            text-decoration: none;
        }

        .hero-links a:hover {
            background: #1d4ed8;
        }

        .container {
            max-width: 1000px;
            margin: 30px auto;
            padding: 0 20px;
        }

        section {
            background: white;
            padding: 28px;
            margin-bottom: 25px;
            border-radius: 10px;
            box-shadow: 0 3px 12px rgba(0,0,0,0.06);
        }

        section h2 {
            color: #2563eb;
            margin-bottom: 18px;
            font-size: 25px;
        }

        .about p {
            text-align: justify;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 18px;
        }

        .skill-box {
            background: #f4f7fc;
            padding: 18px;
            border-radius: 8px;
            border-left: 4px solid #2563eb;
        }

        .skill-box h3 {
            margin-bottom: 8px;
            color: #172554;
            font-size: 17px;
        }

        .skill-box p {
            font-size: 14px;
        }

        .project {
            border: 1px solid #e5e7eb;
            padding: 20px;
            margin-bottom: 18px;
            border-radius: 8px;
            transition: 0.3s;
        }

        .project:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
        }

        .project h3 {
            color: #172554;
            margin-bottom: 8px;
        }

        .project p {
            margin: 6px 0;
        }

        .tech {
            color: #2563eb;
            font-weight: bold;
            font-size: 14px;
        }

        .project a, .contact a {
            color: #2563eb;
            text-decoration: none;
            font-weight: bold;
        }

        .project a:hover, .contact a:hover {
            text-decoration: underline;
        }

        .experience h3 {
            color: #172554;
        }

        .date {
            color: #64748b;
            font-size: 14px;
        }

        ul.details {
            padding-left: 22px;
            margin-top: 10px;
        }

        ul.details li {
            margin-bottom: 8px;
        }

        .achievement-list li {
            margin-bottom: 10px;
        }

        .contact p {
            margin: 10px 0;
        }

        footer {
            background: #101827;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 30px;
        }

        @media (max-width: 650px) {
            nav {
                flex-direction: column;
                gap: 12px;
            }

            nav ul {
                flex-wrap: wrap;
                justify-content: center;
                gap: 12px;
            }

            .hero h1 {
                font-size: 29px;
            }

            .hero p {
                font-size: 16px;
            }

            section {
                padding: 20px;
            }
        }
    </style>
</head>

<body>

    <nav>
        <h2>Gowthami.</h2>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#achievements">Achievements</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <header class="hero">
        <div>
            <h1>THANUBUDDU NAGA GOWTHAMI</h1>
            <p>Software Developer | Machine Learning Enthusiast</p>
            <div class="hero-links">
                <a href="https://github.com/prabha-26" target="_blank">GitHub Profile</a>
                <a href="https://www.linkedin.com/in/naga-gowthami/" target="_blank">LinkedIn</a>
            </div>
        </div>
    </header>

    <main class="container">

        <!-- ABOUT -->
        <section id="about" class="about">
            <h2>About Me</h2>
            <p>
                Hi, I'm Gowthami, a 2026 B.Tech graduate in Data Science
                from Vignan's Foundation for Science, Technology & Research,
                with a CGPA of 8.45. I have a strong foundation in Java,
                Python, Data Structures and Algorithms, and web development.
                I enjoy solving coding problems and building practical
                applications using software engineering and machine learning
                concepts. I am passionate about continuous learning,
                problem-solving, and developing efficient solutions
                to real-world challenges.
            </p>
        </section>

        <!-- SKILLS -->
        <section id="skills">
            <h2>Skills & Expertise</h2>

            <div class="skills-grid">

                <div class="skill-box">
                    <h3>Programming Languages</h3>
                    <p>Java, Python, SQL, JavaScript</p>
                </div>

                <div class="skill-box">
                    <h3>Frontend Development</h3>
                    <p>HTML, CSS, ReactJS</p>
                </div>

                <div class="skill-box">
                    <h3>Backend & APIs</h3>
                    <p>REST APIs</p>
                </div>

                <div class="skill-box">
                    <h3>Frameworks & Libraries</h3>
                    <p>NumPy, Pandas, Matplotlib, TensorFlow, Keras</p>
                </div>

                <div class="skill-box">
                    <h3>Database</h3>
                    <p>MySQL</p>
                </div>

                <div class="skill-box">
                    <h3>AI & Machine Learning</h3>
                    <p>Machine Learning, Deep Learning</p>
                </div>

                <div class="skill-box">
                    <h3>Tools & Platforms</h3>
                    <p>AWS, VS Code, Git, GitHub, Google Colab</p>
                </div>

                <div class="skill-box">
                    <h3>Core Concepts</h3>
                    <p>Data Structures, Algorithms, OOP</p>
                </div>

            </div>
        </section>

        <!-- EXPERIENCE -->
        <section id="experience" class="experience">
            <h2>Experience</h2>

            <h3>Python Programming Language Teaching Assistant</h3>
            <p><strong>Vignan University</strong></p>
            <p class="date">February 2026 – May 2026</p>

            <ul class="details">
                <li>
                    Conducted interactive lectures and doubt-clearing
                    sessions for 200+ students, simplifying complex
                    Python concepts into practical understanding.
                </li>
                <li>
                    Guided students in developing algorithms,
                    completing assignments, and building projects
                    using real-world datasets.
                </li>
            </ul>
        </section>

        <!-- PROJECTS -->
        <section id="projects">
            <h2>My Projects</h2>

            <div class="project">
                <h3>Lung Disease Classification Using ConvNeXt with Coordinate Attention</h3>
                <p class="date">September 2025 – April 2026</p>
                <p>
                    Developed a lightweight ConvNeXt-Nano model with
                    Coordinate Attention to classify four lung disease
                    categories using 21K+ chest X-ray images. Applied
                    CLAHE-based lung masking, preprocessing, data
                    augmentation, and class-weighted training to improve
                    feature extraction and classification.
                </p>
                <p><strong>Result:</strong> Achieved 84% accuracy,
                    improving by 4% over the ConvNeXt-Tiny baseline.</p>
                <p class="tech">
                    Tech Stack: Python, Deep Learning, ConvNeXt,
                    Coordinate Attention, TensorFlow, Keras
                </p>
            </div>

            <div class="project">
                <h3>Plant Disease Detection Using Deep Learning</h3>
                <p class="date">September 2024 – May 2025</p>
                <p>
                    Built an end-to-end plant disease detection pipeline
                    using EfficientNetB0, achieving 98.7% accuracy.
                    Incorporated data augmentation, model optimization,
                    and Grad-CAM for model explainability. Used
                    Google Drive-based model loading for remote access.
                </p>
                <p class="tech">
                    Tech Stack: Python, EfficientNetB0, Deep Learning,
                    Grad-CAM, Google Colab
                </p>
                <a href="#" target="_blank">GitHub Project Link</a>
            </div>

            <div class="project">
                <h3>News Webpage Using APIs</h3>
                <p class="date">August 2024 – November 2024</p>
                <p>
                    Developed a dynamic news web application using
                    RESTful APIs to deliver real-time news data.
                    Implemented caching strategies to reduce page
                    load times by 40% and minimize redundant
                    server requests.
                </p>
                <p class="tech">
                    Tech Stack: HTML, CSS, JavaScript, REST APIs
                </p>
                <a href="#" target="_blank">Project Link</a>
            </div>

            <div class="project">
                <h3>Blood Bank Management System</h3>
                <p class="date">September 2024 – December 2024</p>
                <p>
                    Developed a full-stack web application to manage
                    blood donor details and inventory records.
                    Implemented CRUD operations, input validation,
                    and efficient data retrieval, helping reduce
                    manual data entry time by 20%.
                </p>
                <p class="tech">
                    Tech Stack: PHP, MySQL, HTML, CSS, JavaScript
                </p>
                <a href="#" target="_blank">GitHub Project Link</a>
            </div>

        </section>

        <!-- ACHIEVEMENTS -->
        <section id="achievements">
            <h2>Achievements & Certifications</h2>

            <ul class="details achievement-list">
                <li>
                    Solved 200+ Data Structures and Algorithms
                    problems on LeetCode and CodeChef.
                </li>
                <li>Data Analytics Using Python – NPTEL.</li>
                <li>Learning Analytics Tools – NPTEL.</li>
                <li>Python Essentials 1 – Cisco.</li>
            </ul>
        </section>

        <!-- PUBLICATIONS -->
        <section id="publications">
            <h2>Research Publication</h2>

            <h3>
                Lung Disease Classification from Chest X-Rays Using
                ConvNeXt with Coordinate Attention on the COVID-19
                Radiography Dataset
            </h3>

            <p>
                Co-authored research paper published in the
                Proceedings of the 8th International Conference on
                Inventive Material Science and Applications
                (ICIMA 2026), IEEE.
            </p>
        </section>

        <!-- EDUCATION -->
        <section id="education">
            <h2>Education</h2>

            <h3>B.Tech – Data Science</h3>
            <p>Vignan's Foundation for Science, Technology & Research</p>
            <p class="date">2022 – 2026 | CGPA: 8.45/10</p>

            <br>

            <h3>Intermediate – MPC</h3>
            <p>Vignan Junior College</p>
            <p class="date">2020 – 2022 | 97%</p>

            <br>

            <h3>SSC</h3>
            <p>Naveena High School</p>
            <p class="date">2020 | 96%</p>
        </section>

        <!-- CONTACT -->
        <section id="contact" class="contact">
            <h2>Connect With Me</h2>

            <p>
                <strong>Email:</strong>
                <a href="mailto:thanubuddunagagowthami@gmail.com">
                    thanubuddunagagowthami@gmail.com
                </a>
            </p>

            <p>
                <strong>LinkedIn:</strong>
                <a href="https://www.linkedin.com/in/naga-gowthami/"
                   target="_blank">
                    LinkedIn Profile
                </a>
            </p>

            <p>
                <strong>GitHub:</strong>
                <a href="https://github.com/prabha-26"
                   target="_blank">
                    GitHub Profile
                </a>
            </p>
        </section>

    </main>

    <footer>
        <p>© 2026 Naga Gowthami. All Rights Reserved.</p>
    </footer>

</body>
</html>
