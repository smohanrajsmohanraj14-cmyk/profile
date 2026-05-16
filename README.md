<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Professional portfolio website showcasing skills, projects, and experience.">
    <title>Mohanraj - Portfolio</title>
    
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
    
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <link rel="stylesheet" href="portfolio.css">
</head>
<body>
    <nav class="navbar">
        <div class="nav-container">
            <div class="logo">
                <i class="fas fa-code"></i> Mohanraj
            </div>
            <ul class="nav-menu">
                <li><a href="#home" class="nav-link">Home</a></li>
                <li><a href="#about" class="nav-link">About</a></li>
                <li><a href="#skills" class="nav-link">Skills</a></li>
                <li><a href="#projects" class="nav-link">Projects</a></li>
                <li><a href="#education" class="nav-link">Education</a></li>
                <li><a href="#contact" class="nav-link">Contact</a></li>
            </ul>
            <div class="hamburger">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </nav>

    <section id="home" class="home">
        <div class="container">
            <div class="home-content">
                <div class="home-text">
                    <h1 class="home-title">Hi, I'm Mohanraj</h1>
                    <p class="home-subtitle">Web Developer</p>
                    <p class="home-description">
                        Welcome to my portfolio! I'm passionate about creating beautiful, functional, and user-friendly web applications. 
                        With expertise in both frontend and backend technologies, I love solving complex problems and building innovative solutions.
                    </p>
                    <div class="home-buttons">
                        <a href="#contact" class="btn btn-primary">Get In Touch</a>
                        <a href="#projects" class="btn btn-secondary">View My Work</a>
                    </div>
                </div>
                <div class="home-image">
                    <div class="profile-image">
                        <img src="" alt="" class="img-responsive">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="about">
        <div class="container">
            <h2 class="section-title">About Me</h2>
            <div class="about-content">
                <div class="about-text">
                    <h3>Who I Am</h3>
                    <p>
                        I'm a passionate and dedicated web developer focused on building modern web applications. 
                        I specialize in creating responsive, scalable, and user-centric solutions that solve real-world problems.
                    </p>
                    <p>
                        My journey in web development started with a curiosity about how websites work, which evolved into deep diving into multiple technologies and frameworks. I'm committed to continuous learning and staying updated with the latest industry trends.
                    </p>
                    <h3>Education & Career Objective</h3>
                    <p>
                        <strong>Degree:</strong> Bachelor of Computer Application (BCA)<br>
                        <strong>College:</strong> K.M.G College of Arts and Science<br>
                        <strong>Year:</strong> 2024 - 2027
                    </p>
                    <p>
                        <strong>Career Objective:</strong> To leverage my technical skills and creative problem-solving abilities to build innovative web solutions 
                        that provide value to users and businesses. I'm particularly interested in full-stack development, cloud technologies, and DevOps practices.
                    </p>
                </div>
                <div class="about-highlights">
                    <div class="highlight-card">
                        <i class="fas fa-code"></i>
                        <h4>Clean Code</h4>
                        <p>Writing maintainable and scalable code following best practices</p>
                    </div>
                    <div class="highlight-card">
                        <i class="fas fa-mobile-alt"></i>
                        <h4>Responsive Design</h4>
                        <p>Creating websites that work seamlessly on all devices</p>
                    </div>
                    <div class="highlight-card">
                        <i class="fas fa-rocket"></i>
                        <h4>Performance</h4>
                        <p>Optimizing applications for speed and efficiency</p>
                    </div>
                    <div class="highlight-card">
                        <i class="fas fa-users"></i>
                        <h4>Collaboration</h4>
                        <p>Working effectively with teams to deliver great results</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="skills" class="skills">
        <div class="container">
            <h2 class="section-title">My Skills</h2>
            <div class="skills-grid">
                <div class="skill-category">
                    <h3>Frontend Development</h3>
                    <div class="skill-item">
                        <div class="skill-header">
                            <span class="skill-name">HTML5 & CSS3</span>
                            <span class="skill-percentage">96%</span>
                        </div>
                        <div class="progress-bar">
                            <div class="progress-fill" style="width: 96%"></div>
                        </div>
                    </div>
                    <div class="skill-item">
                        <div class="skill-header">
                            <span class="skill-name">JavaScript</span>
                            <span class="skill-percentage">80%</span>
                        </div>
                        <div class="progress-bar">
                            <div class="progress-fill" style="width: 80%"></div>
                        </div>
                    </div>
                    <div class="skill-item">
                        <div class="skill-header">
                            <span class="skill-name">React.js</span>
                            <span class="skill-percentage">65%</span>
                        </div>
                        <div class="progress-bar">
                            <div class="progress-fill" style="width: 65%"></div>
                        </div>
                    </div>
                </div>

                <div class="skill-category">
                    <h3>Backend Development</h3>
                    <div class="skill-item">
                        <div class="skill-header">
                            <span class="skill-name">Node.js</span>
                            <span class="skill-percentage">75%</span>
                        </div>
                        <div class="progress-bar">
                            <div class="progress-fill" style="width: 75%"></div>
                        </div>
                    </div>
                    <div class="skill-item">
                        <div class="skill-header">
                            <span class="skill-name">Python</span>
                            <span class="skill-percentage">82%</span>
                        </div>
                        <div class="progress-bar">
                            <div class="progress-fill" style="width: 82%"></div>
                        </div>
                    </div>
                    <div class="skill-item">
                        <div class="skill-header">
                            <span class="skill-name">Java</span>
                            <span class="skill-percentage">80%</span>
                        </div>
                        <div class="progress-bar">
                            <div class="progress-fill" style="width: 80%"></div>
                        </div>
                    </div>
                </div>

                <div class="skill-category">
                    <h3>Other Skills</h3>
                    <div class="skill-item">
                        <div class="skill-header">
                            <span class="skill-name">Databases (MySQL, MongoDB)</span>
                            <span class="skill-percentage">85%</span>
                        </div>
                        <div class="progress-bar">
                            <div class="progress-fill" style="width: 85%"></div>
                        </div>
                    </div>
                    <div class="skill-item">
                        <div class="skill-header">
                            <span class="skill-name">Git & Version Control</span>
                            <span class="skill-percentage">90%</span>
                        </div>
                        <div class="progress-bar">
                            <div class="progress-fill" style="width: 90%"></div>
                        </div>
                    </div>
                    <div class="skill-item">
                        <div class="skill-header">
                            <span class="skill-name">REST APIs</span>
                            <span class="skill-percentage">88%</span>
                        </div>
                        <div class="progress-bar">
                            <div class="progress-fill" style="width: 88%"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="projects" class="projects">
        <div class="container">
            <h2 class="section-title">My Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <div class="project-image">
                        <i class="fas fa-graduation-cap"></i>
                    </div>
                    <div class="project-content">
                        <h3>Student Management System</h3>
                        <p>
                            A comprehensive web-based system for managing student records, attendance, grades, and communications. 
                            Built with a user-friendly interface for administrators and teachers.
                        </p>
                        <div class="project-tech">
                            <span class="tech-tag">HTML5</span>
                            <span class="tech-tag">CSS3</span>
                            <span class="tech-tag">JavaScript</span>
                            <span class="tech-tag">Python</span>
                            <span class="tech-tag">MySQL</span>
                        </div>
                        <div class="project-links">
                            <a href="#" class="project-link">
                                <i class="fas fa-external-link-alt"></i> View Project
                            </a>
                            <a href="#" class="project-link">
                                <i class="fas fa-code"></i> Source Code
                            </a>
                        </div>
                    </div>
                </div>

                <div class="project-card">
                    <div class="project-image">
                        <i class="fas fa-video"></i>
                    </div>
                    <div class="project-content">
                        <h3>Online Interview Portal</h3>
                        <p>
                            An interactive platform for conducting online interviews with features like real-time video conferencing, 
                            code editor, and automated evaluation. Perfect for technical and non-technical interviews.
                        </p>
                        <div class="project-tech">
                            <span class="tech-tag">React.js</span>
                            <span class="tech-tag">Node.js</span>
                            <span class="tech-tag">WebRTC</span>
                            <span class="tech-tag">MongoDB</span>
                            <span class="tech-tag">Socket.io</span>
                        </div>
                        <div class="project-links">
                            <a href="#" class="project-link">
                                <i class="fas fa-external-link-alt"></i> View Project
                            </a>
                            <a href="#" class="project-link">
                                <i class="fas fa-code"></i> Source Code
                            </a>
                        </div>
                    </div>
                </div>

                <div class="project-card">
                    <div class="project-image">
                        <i class="fas fa-link"></i>
                    </div>
                    <div class="project-content">
                        <h3>Blockchain File Sharing System</h3>
                        <p>
                            A decentralized file sharing platform leveraging blockchain technology for secure, transparent, 
                            and immutable file transfers. Supports encryption and smart contracts for access control.
                        </p>
                        <div class="project-tech">
                            <span class="tech-tag">Solidity</span>
                            <span class="tech-tag">Ethereum</span>
                            <span class="tech-tag">React.js</span>
                            <span class="tech-tag">Web3.js</span>
                            <span class="tech-tag">IPFS</span>
                        </div>
                        <div class="project-links">
                            <a href="#" class="project-link">
                                <i class="fas fa-external-link-alt"></i> View Project
                            </a>
                            <a href="#" class="project-link">
                                <i class="fas fa-code"></i> Source Code
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="education" class="education">
        <div class="container">
            <h2 class="section-title">Education</h2>
            <div class="education-timeline">
                <div class="timeline-item">
                    <div class="timeline-marker">
                        <i class="fas fa-graduation-cap"></i>
                    </div>
                    <div class="timeline-content">
                        <h3>Bachelor of Computer Application (BCA)</h3>
                        <p class="education-school">
                            <i class="fas fa-university"></i> K.M.G COLLEGE OF ARTS AND SCIENCE
                        </p>
                        <p class="education-year">2024 - 2027</p>
                        <p class="education-details">
                            Major: Computer Application<br>
                            CGPA: 8.5/10<br>
                            Relevant Coursework: Data Structures, Web Development, Object-Oriented Programming, Database Management Systems
                        </p>
                    </div>
                </div>

                <div class="timeline-item">
                    <div class="timeline-marker">
                        <i class="fas fa-certificate"></i>
                    </div>
                    <div class="timeline-content">
                        <h3>Full Stack Web Development Certification</h3>
                        <p class="education-school">
                            <i class="fas fa-book"></i> Udemy Online Learning Platform
                        </p>
                        <p class="education-year">2024</p>
                        <p class="education-details">
                            Comprehensive course covering HTML5, CSS3, JavaScript, React, Node.js, and MongoDB. 
                            Completed 15+ projects with real-world applications.
                        </p>
                    </div>
                </div>

                <div class="timeline-item">
                    <div class="timeline-marker">
                        <i class="fas fa-trophy"></i>
                    </div>
                    <div class="timeline-content">
                        <h3>Advanced JavaScript & React Specialization</h3>
                        <p class="education-school">
                            <i class="fas fa-book"></i> Coursera - Advanced Web Development
                        </p>
                        <p class="education-year">2025</p>
                        <p class="education-details">
                            Specialized training in modern JavaScript patterns, React hooks, state management (Redux), 
                            and advanced web development practices.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2 class="section-title">Get In Touch</h2>
            <p class="contact-intro">Have a project in mind or just want to chat? Feel free to reach out!</p>
            
            <div class="contact-content">
                <div class="contact-info">
                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="fas fa-envelope"></i>
                        </div>
                        <div class="contact-details">
                            <h4>Email</h4>
                            <a href="mailto:smohanrajsmohanraj14@gmail.com">smohanrajsmohanraj14@gmail.com</a>
                        </div>
                    </div>

                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="fas fa-phone"></i>
                        </div>
                        <div class="contact-details">
                            <h4>Phone</h4>
                            <a href="tel:+918531885364">+91 8531885364</a>
                        </div>
                    </div>

                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="fas fa-map-marker-alt"></i>
                        </div>
                        <div class="contact-details">
                            <h4>Location</h4>
                            <p>Vellore, Tamil Nadu, India</p>
                        </div>
                    </div>

                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="fas fa-globe"></i>
                        </div>
                        <div class="contact-details">
                            <h4>Social Links</h4>
                            <div class="social-links">
                                <a href="https://github.com" target="_blank" title="GitHub">
                                    <i class="fab fa-github"></i>
                                </a>
                                <a href="https://instagram.com" target="_blank" title="Instagram">
                                    <i class="fab fa-instagram"></i>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <form class="contact-form">
                    <div class="form-group">
                        <label for="name">Name</label>
                        <input type="text" id="name" name="name" required>
                    </div>
                    <div class="form-group">
                        <label for="email">Email</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    <div class="form-group">
                        <label for="subject">Subject</label>
                        <input type="text" id="subject" name="subject" required>
                    </div>
                    <div class="form-group">
                        <label for="message">Message</label>
                        <textarea id="message" name="message" rows="5" required></textarea>
                    </div>
                    <button type="submit" class="btn btn-primary">Send Message</button>
                </form>
            </div>
        </div>
    </section>

    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <p>&copy; 2027 MohanRaj. All rights reserved.</p>
                <p>Designed by <strong>MohanRaj</strong></p>
            </div>
        </div>
    </footer>

    <script>
        // Smooth scrolling
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Mobile menu toggle
        const hamburger = document.querySelector('.hamburger');
        const navMenu = document.querySelector('.nav-menu');

        hamburger.addEventListener('click', () => {
            navMenu.classList.toggle('active');
            hamburger.classList.toggle('active');
        });

        // Close mobile menu when a link is clicked
        document.querySelectorAll('.nav-link').forEach(link => {
            link.addEventListener('click', () => {
                navMenu.classList.remove('active');
                hamburger.classList.remove('active');
            });
        });

        // Form submission
        document.querySelector('.contact-form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you for your message! I will get back to you soon.');
            this.reset();
        });
    </script>
</body>
</html>
