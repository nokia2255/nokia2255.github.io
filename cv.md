---
layout: default
title: ZhangJing Mok's CV
---

Here's where you can learn more about me.

<style>
    /* ===== 全局样式 ===== */
    :root {
        --primary: #6e8efb;
        --secondary: #a777e3;
        --dark: #2d3748;
        --light: #f7fafc;
        --gray: #e2e8f0;
    }
    
    .about-container {
        max-width: 1200px;
        margin: 0 auto;
        padding: 2rem;
    }
    
    /* ===== 英雄区 ===== */
    .about-hero {
        display: flex;
        align-items: center;
        gap: 3rem;
        margin-bottom: 4rem;
    }
    
    .profile-img {
        width: 250px;
        height: 250px;
        border-radius: 50%;
        object-fit: cover;
        border: 5px solid white;
        box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    }
    
    .hero-text h1 {
        font-size: 2.8rem;
        margin-bottom: 1rem;
        background: linear-gradient(to right, var(--primary), var(--secondary));
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
    }
    
    .hero-text p {
        font-size: 1.2rem;
        line-height: 1.8;
        color: var(--dark);
    }
    
    /* ===== 时间轴 ===== */
    .timeline {
        position: relative;
        padding-left: 50px;
        margin: 3rem 0;
    }
    
    .timeline::before {
        content: '';
        position: absolute;
        left: 15px;
        top: 0;
        height: 100%;
        width: 3px;
        background: linear-gradient(to bottom, var(--primary), var(--secondary));
    }
    
    .timeline-item {
        position: relative;
        margin-bottom: 2.5rem;
        padding: 1.5rem;
        background: white;
        border-radius: 10px;
        box-shadow: 0 5px 15px rgba(0,0,0,0.05);
    }
    
    .timeline-item::before {
        content: '';
        position: absolute;
        left: -40px;
        top: 20px;
        width: 20px;
        height: 20px;
        border-radius: 50%;
        background: var(--primary);
        border: 3px solid white;
    }
    
    .timeline-date {
        color: var(--secondary);
        font-weight: 600;
        margin-bottom: 0.5rem;
    }
    
    /* ===== 技能图表 ===== */
    .skills-section {
        background: var(--gray);
        padding: 3rem;
        border-radius: 15px;
        margin: 3rem 0;
    }
    
    .skills-grid {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
        gap: 1.5rem;
    }
    
    .skill-card {
        background: white;
        padding: 1.5rem;
        border-radius: 10px;
        text-align: center;
        transition: all 0.3s ease;
    }
    
    .skill-card:hover {
        transform: translateY(-5px);
        box-shadow: 0 10px 20px rgba(0,0,0,0.1);
    }
    
    .skill-icon {
        font-size: 2.5rem;
        margin-bottom: 1rem;
        color: var(--primary);
    }
    
    /* ===== 兴趣区域 ===== */
    .interests-section {
        margin: 3rem 0;
    }
    
    .interest-tags {
        display: flex;
        flex-wrap: wrap;
        gap: 1rem;
    }
    
    .interest-tag {
        background: linear-gradient(to right, var(--primary), var(--secondary));
        color: white;
        padding: 0.5rem 1.2rem;
        border-radius: 20px;
        font-size: 0.9rem;
    }
    
    /* ===== 响应式设计 ===== */
    @media (max-width: 768px) {
        .about-hero {
            flex-direction: column;
            text-align: center;
        }
        
        .profile-img {
            margin-bottom: 1.5rem;
        }
    }
</style>

<div class="about-container">
    <!-- 英雄区 -->
    <section class="about-hero">
        <img src="{{ site.baseurl }}/images/profile_pic.jpg" alt="ZhangJing Mok" class="profile-img">
        <div class="hero-text">
            <h1>ZhangJing Mok</h1>
            <p>Mobile Developer | Problem Solver | Tech Enthusiast</p>
            <p>Specializing in Mobile Application Development with a passion for creating intuitive user experiences and solving complex problems through code.</p>
        </div>
    </section>
    <!-- 教育背景 -->
    <section>
        <h2>🎓 Education</h2>
        <div class="timeline">
            <div class="timeline-item">
                <div class="timeline-date">2019 - 2023</div>
                <h3>Universiti Tunku Abdul Rahman</h3>
                <p>Bachelor of Computer Science (Mobile Application Development)</p>
                <p>GPA: 3.8/4.0 | Dean's List for 5 semesters</p>
            </div>
        </div>
    </section>
    <!-- 专业技能 -->
    <section class="skills-section">
        <h2>🛠 Technical Skills</h2>
        <div class="skills-grid">
            <div class="skill-card">
                <div class="skill-icon"><i class="fas fa-mobile-alt"></i></div>
                <h3>Mobile Development</h3>
                <p>Flutter, Android, iOS, React Native</p>
            </div>
            <div class="skill-card">
                <div class="skill-icon"><i class="fas fa-code"></i></div>
                <h3>Frontend</h3>
                <p>HTML/CSS, JavaScript, React</p>
            </div>
            <div class="skill-card">
                <div class="skill-icon"><i class="fas fa-server"></i></div>
                <h3>Backend</h3>
                <p>Node.js, Firebase, MongoDB</p>
            </div>
            <div class="skill-card">
                <div class="skill-icon"><i class="fas fa-project-diagram"></i></div>
                <h3>Tools</h3>
                <p>Git, Docker, Figma</p>
            </div>
        </div>
    </section>
    <!-- 工作经验 -->
    <section>
        <h2>💼 Work Experience</h2>
        <div class="timeline">
            <div class="timeline-item">
                <div class="timeline-date">2022 - Present</div>
                <h3>Mobile Developer @ TechSolutions Inc.</h3>
                <ul>
                    <li>Developed cross-platform mobile app with Flutter</li>
                    <li>Improved app performance by 40%</li>
                    <li>Implemented CI/CD pipeline</li>
                </ul>
            </div>
            <div class="timeline-item">
                <div class="timeline-date">2021 - 2022</div>
                <h3>Intern @ Digital Creations</h3>
                <ul>
                    <li>Assisted in Android app development</li>
                    <li>Conducted user testing sessions</li>
                </ul>
            </div>
        </div>
    </section>
    <!-- 兴趣爱好 -->
    <section class="interests-section">
        <h2>❤️ Interests</h2>
        <div class="interest-tags">
            <span class="interest-tag">Mobile UI/UX</span>
            <span class="interest-tag">Augmented Reality</span>
            <span class="interest-tag">Gaming</span>
            <span class="interest-tag">Photography</span>
            <span class="interest-tag">Hiking</span>
        </div>
    </section>
    <!-- 联系区块 -->
    <section style="text-align: center; margin-top: 4rem;">
        <h2>Let's Connect!</h2>
        <p>Feel free to reach out for collaborations or just a friendly chat</p>
        <div style="display: flex; justify-content: center; gap: 1.5rem; margin-top: 1rem;">
            <a href="mailto:your.email@example.com" style="font-size: 1.5rem;"><i class="fas fa-envelope"></i></a>
            <a href="https://github.com/yourusername" style="font-size: 1.5rem;"><i class="fab fa-github"></i></a>
            <a href="https://linkedin.com/in/yourprofile" style="font-size: 1.5rem;"><i class="fab fa-linkedin"></i></a>
        </div>
    </section>
</div>

<!-- 添加 Font Awesome -->
<script src="https://kit.fontawesome.com/your-code.js" crossorigin="anonymous"></script>
