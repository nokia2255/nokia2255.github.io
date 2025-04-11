---
layout: default
title: ZhangJing Mok's CV
---

Here is where you can learn more about me.

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
            <p>Solutions Architect | Problem Solver | Data Analyst</p>
            <p>Specializing in Convergent Billing System and solving complex problems.</p>
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
                <p>GPA: 3.6/4.0</p>
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
                <p>Flutter, Android, iOS</p>
            </div>
            <div class="skill-card">
                <div class="skill-icon"><i class="fas fa-code"></i></div>
                <h3>Frontend</h3>
                <p>HTML/CSS, JavaScript, React</p>
            </div>
            <div class="skill-card">
                <div class="skill-icon"><i class="fas fa-server"></i></div>
                <h3>Data Analysis</h3>
                <p>SQL, Excel, Python</p>
            </div>
            <div class="skill-card">
                <div class="skill-icon"><i class="fas fa-project-diagram"></i></div>
                <h3>Tools</h3>
                <p>Dbeaver, Pycharm, SoapUi</p>
            </div>
        </div>
    </section>
    <!-- 工作经验 -->
    <section>
        <h2>💼 Work Experience</h2>
        <div class="timeline">
            <div class="timeline-item">
                <div class="timeline-date">2022 - Present</div>
                <h3>Huawei Solutions Architect </h3>
                <ul>
                    <li>Design the solution of the delivery project (mainly focusing on convergent billing system(CBS))</li>
                    <li>Led two interns and some juniors, guiding them through hand-on tasks and fostering their professional development in telco industry</li>
                </ul>
            </div>
            <div class="timeline-item">
                <div class="timeline-date">2021 - 2022</div>
                <h3>Huawei AP Project Engineer Intern </h3>
                <ul>
                    <li>Review site installation quality remotely</li>
                    <li>Review site subcontractors safety remotely</li>
                    <li>Audit site installation and safety remotely</li>
                    <li>Support data analysis on rejected quality and safety checks</li>
                    <li>Generate daily report by using Python programming language</li>
                    <li>Guide and Contact subcontractor for rectification of site installation</li>
                </ul>
            </div>
        </div>
    </section>
</div>
