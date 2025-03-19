<!-- index.html -->
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的个人简介</title>
    <link rel="stylesheet" href="style.css">
    <link rel="icon" href="favicon.ico" type="image/x-icon">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home" class="active">首页</a></li>
                <li><a href="#about">关于我</a></li>
                <li><a href="#skills">技能</a></li>
                <li><a href="#contact">联系我</a></li>
            </ul>
        </nav>
    </header>
 
    <main>
        <section id="home" class="hero">
            <div class="container">
                <h1>你好！我是张三</h1>
                <p>全栈开发者 | 技术爱好者 | 终身学习者</p>
                <a href="#contact" class="cta-button">立即联系</a>
            </div>
        </section>
 
        <section id="about" class="content-section">
            <div class="container">
                <h2>关于我</h2>
                <p>拥有5年前端开发经验，熟悉React/Vue技术栈，热爱开源社区，喜欢探索新技术。</p>
                <div class="profile-card">
                    <img src="profile.jpg" alt="个人照片" class="avatar">
                    <div class="card-content">
                        <h3>专业方向</h3>
                        <ul>
                            <li>Web开发</li>
                            <li>响应式设计</li>
                            <li>性能优化</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>
 
        <section id="skills" class="content-section">
            <div class="container">
                <h2>技术技能</h2>
                <div class="skill-grid">
                    <div class="skill-card">
                        <h3>前端开发</h3>
                        <ul>
                            <li>HTML5/CSS3</li>
                            <li>JavaScript/ES6+</li>
                            <li>React/Vue</li>
                        </ul>
                    </div>
                    <div class="skill-card">
                        <h3>后端开发</h3>
                        <ul>
                            <li>Node.js</li>
                            <li>Python/Django</li>
                            <li>MySQL/MongoDB</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>
 
        <section id="contact" class="content-section">
            <div class="container">
                <h2>联系我</h2>
                <div class="contact-info">
                    <a href="mailto:zhangsan@example.com" class="contact-link">
                        <i class="fas fa-envelope"></i> zhangsan@example.com
                    </a>
                    <a href="https://github.com/yourusername" target="_blank" class="contact-link">
                        <i class="fab fa-github"></i> GitHub
                    </a>
                    <a href="https://linkedin.com/in/yourprofile" target="_blank" class="contact-link">
                        <i class="fab fa-linkedin"></i> LinkedIn
                    </a>
                </div>
            </div>
        </section>
    </main>
 
    <footer>
        <p>&copy; 2023 张三. 保留所有权利。</p>
    </footer>
 
    <script src="https://kit.fontawesome.com/your-font-awesome-code.js"></script>
    <script src="script.js"></script>
</body>
</html>
