<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>施梦娇 | 资源与环境硕士</title>
    <style>
        body {
            margin: 0;
            min-height: 100vh;
            background: linear-gradient(135deg, #2980b9, #87CEEB, #ffffff);
            background-size: 300% 300%;
            animation: gradientFlow 12s ease infinite;
            font-family: 'Microsoft YaHei', sans-serif;
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
            padding: 2.5rem;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            text-align: center;
            max-width: 90%;
            width: 450px;
            backdrop-filter: blur(10px);
        }
 
        .avatar {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 1.5rem;
            border: 4px solid #2980b9;
            transition: transform 0.3s ease;
        }
 
        .avatar:hover {
            transform: rotate(5deg);
        }
 
        h1 {
            color: #2c3e50;
            margin: 0 0 0.8rem 0;
            font-size: 2.4rem;
            font-weight: 700;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
        }
 
        h2 {
            color: #3498db;
            margin: 0 0 1.5rem 0;
            font-size: 1.2rem;
            letter-spacing: 2px;
            font-weight: 500;
        }
 
        p {
            color: #34495e;
            line-height: 1.8;
            margin-bottom: 2rem;
            font-size: 1.1rem;
        }
 
        .skills {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
            gap: 20px;
            justify-content: center;
            margin: 1.5rem 0;
        }
 
        .skill-tag {
            background: #2980b9;
            color: white;
            padding: 10px 15px;
            border-radius: 25px;
            font-size: 0.9rem;
            transition: all 0.3s ease;
        }
 
        .skill-tag:hover {
            transform: translateY(-3px);
            background: #3498db;
            box-shadow: 0 5px 15px rgba(52,152,219,0.3);
        }
 
        .contact {
            margin-top: 2rem;
            display: flex;
            justify-content: center;
            gap: 25px;
            flex-wrap: wrap;
        }
 
        .contact a {
            color: #2c3e50;
            font-size: 1.5rem;
            transition: color 0.3s ease;
        }
 
        .contact a:hover {
            color: #3498db;
        }
    </style>
</head>
<body>
    <div class="profile-card">
        <img src="https://via.placeholder.com/180" alt="施梦娇" class="avatar">
        <h1>施梦娇</h1>
        <h2>资源与环境专业硕士研究生</h2>
        <p>专注于环境数据分析与可持续发展研究，擅长运用GIS技术进行空间数据分析，具备环境评估与生态修复项目经验。熟悉Python数据分析和Matlab建模，致力于通过技术创新推动绿色解决方案。</p>
 
        <div class="skills">
            <div class="skill-tag">GIS分析</div>
            <div class="skill-tag">环境建模</div>
            <div class="skill-tag">Python</div>
            <div class="skill-tag">Matlab</div>
            <div class="skill-tag">生态评估</div>
            <div class="skill-tag">可持续发展</div>
        </div>
 
        <div class="contact">
            <a href="mailto:your@email.com" target="_blank">📧 联系我</a>
            <a href="https://github.com" target="_blank">🐙 GitHub</a>
            <a href="https://linkedin.com" target="_blank">🌐 LinkedIn</a>
        </div>
    </div>
</body>
</html>
