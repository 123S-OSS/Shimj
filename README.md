<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🌈 我的自我介绍</title>
    <style>
        /* 色彩鲜明的渐变背景 */
        body {
            margin: 0;
            min-height: 100vh;
            background: linear-gradient(45deg, #ff6b6b, #4ecdc4, #45b7d1);
            background-size: 400% 400%;
            animation: gradientBG 15s ease infinite;
            font-family: 'Segoe UI', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
        }
 
        /* 背景动画 */
        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
 
        /* 主内容容器 */
        .profile-card {
            background: rgba(255, 255, 255, 0.95);
            padding: 2rem;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
            text-align: center;
            max-width: 90%;
            width: 400px;
        }
 
        /* 头像样式 */
        .avatar {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 1.5rem;
            border: 4px solid white;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
        }
 
        /* 标题样式 */
        h1 {
            color: #2c3e50;
            margin: 0 0 1rem 0;
            font-size: 2.5rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
        }
 
        /* 副标题样式 */
        h2 {
            color: #e74c3c;
            margin: 0 0 1.5rem 0;
            font-size: 1.2rem;
            letter-spacing: 2px;
        }
 
        /* 技能标签 */
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            justify-content: center;
            margin: 2rem 0;
        }
 
        .skill-tag {
            background: #3498db;
            color: white;
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            transition: transform 0.3s ease;
        }
 
        .skill-tag:hover {
            transform: translateY(-2px);
        }
 
        /* 社交链接 */
        .social-links a {
            color: #2c3e50;
            margin: 0 10px;
            font-size: 1.5rem;
            transition: color 0.3s ease;
        }
 
        .social-links a:hover {
            color: #e74c3c;
        }
    </style>
</head>
<body>
    <div class="profile-card">
        <img src="https://via.placeholder.com/150" alt="头像" class="avatar">
        <h1>张 三</h1>
        <h2>全栈开发工程师</h2>
        
        <p>热爱编程与设计的极客，擅长将创意转化为数字产品。拥有5年Web开发经验，专注于前端性能优化与用户体验设计。</p>
 
        <div class="skills">
            <div class="skill-tag">HTML5</div>
            <div class="skill-tag">CSS3</div>
            <div class="skill-tag">JavaScript</div>
            <div class="skill-tag">React</div>
            <div class="skill-tag">Node.js</div>
            <div class="skill-tag">Git</div>
        </div>
 
        <div class="social-links">
            <a href="#" target="_blank">🌐 个人网站</a>
            <a href="#" target="_blank">📧 联系邮箱</a>
            <a href="#" target="_blank">🐦 Twitter</a>
        </div>
    </div>
</body>
</html>
