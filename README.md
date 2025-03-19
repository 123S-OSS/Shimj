<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>🌐 我的蓝色空间</title>
    <style>
        body {
            margin: 0;
            min-height: 100vh;
            background: linear-gradient(135deg, #2980b9, #3498db, #2980b9);
            background-size: 300% 300%;
            animation: gradientFlow 8s ease infinite;
            font-family: 'Segoe UI', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
        }
 
        @keyframes gradientFlow {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
 
        .profile-card {
            background: rgba(255, 255, 255, 0.95);
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 8px 25px rgba(0,0,0,0.15);
            text-align: center;
            max-width: 95%;
            width: 400px;
            backdrop-filter: blur(10px);
        }
 
        .avatar {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 1.5rem;
            border: 3px solid #3498db;
        }
 
        h1 {
            color: #2c3e50;
            margin: 0 0 1rem 0;
            font-size: 2.2rem;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
        }
 
        h2 {
            color: #3498db;
            margin: 0 0 1.2rem 0;
            font-size: 1.1rem;
            letter-spacing: 1.5px;
        }
 
        p {
            color: #34495e;
            line-height: 1.6;
            margin-bottom: 1.5rem;
        }
 
        .skills {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(100px, 1fr));
            gap: 15px;
            justify-content: center;
            margin: 1.5rem 0;
        }
 
        .skill-tag {
            background: #2980b9;
            color: white;
            padding: 8px 12px;
            border-radius: 15px;
            font-size: 0.85rem;
            transition: transform 0.2s ease;
        }
 
        .skill-tag:hover {
            transform: translateY(-2px);
            background: #3498db;
        }
 
        .social-links a {
            color: #2c3e50;
            margin: 0 12px;
            font-size: 1.3rem;
            transition: color 0.2s ease;
        }
 
        .social-links a:hover {
            color: #3498db;
        }
    </style>
</head>
<body>
    <div class="profile-card">
        <img src="https://via.placeholder.com/150" alt="个人头像" class="avatar">
        <h1>施梦娇</h1>
        <h2>Web硕士研究生</h2>
        <p>专注环境保护，热爱环保事业。擅长废水处理技术，对厌氧氨氧化工艺处理废水有深入研究。</p>
        
        <div class="skills">
            <div class="skill-tag">HTML5</div>
            <div class="skill-tag">CSS3</div>
            <div class="skill-tag">JavaScript</div>
            <div class="skill-tag">Vue.js</div>
            <div class="skill-tag">Webpack</div>
            <div class="skill-tag">Git</div>
        </div>
 
        <div class="social-links">
            <a href="#" target="_blank">🌐 12409866356</a>
            <a href="#" target="_blank">📧 1076432876@qq.com</a>
            <a href="#" target="_blank">🐦 Twitter</a>
        </div>
    </div>
</body>
</html>
