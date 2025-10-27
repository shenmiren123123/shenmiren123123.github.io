<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>YADI SANG 的主页</title>
    <style>
        /* 基本样式 */
        body {
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 40px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            margin: 10px 0 0;
            font-size: 1.2em;
        }
        nav {
            text-align: center;
            margin: 20px 0;
        }
        nav a {
            margin: 0 20px;
            text-decoration: none;
            color: #4CAF50;
            font-weight: bold;
            font-size: 1.1em;
        }
        nav a:hover {
            color: #333;
        }
        main {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 15px rgba(0,0,0,0.05);
        }
        section {
            margin-bottom: 40px;
        }
        section h2 {
            border-bottom: 2px solid #4CAF50;
            padding-bottom: 5px;
        }
        footer {
            text-align: center;
            padding: 20px 0;
            background-color: #eee;
            color: #666;
        }
        @media (max-width: 600px) {
            nav a {
                display: block;
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>YADI SANG 的主页</h1>
        <p>分享我的学习、项目与生活</p>
    </header>

    <nav>
        <a href="#about">关于我</a>
        <a href="#projects">项目展示</a>
        <a href="#contact">联系我</a>
    </nav>

    <main>
        <section id="about">
            <h2>关于我</h2>
            <p>你好，我是 YADI SANG，一个热爱技术和创作的人。我喜欢写代码、搭建网站，也喜欢分享经验和知识。</p>
        </section>

        <section id="projects">
            <h2>项目展示</h2>
            <ul>
                <li>个人博客：记录学习笔记与技术文章</li>
                <li>GitHub Pages 网站：展示个人作品和小工具</li>
                <li>小工具合集：各种实用工具和脚本</li>
            </ul>
        </section>

        <section id="contact">
            <h2>联系我</h2>
            <p>邮箱：<a href="mailto:youremail@example.com">youremail@example.com</a></p>
            <p>GitHub: <a href="https://github.com/你的用户名" target="_blank">https://github.com/你的用户名</a></p>
        </section>
    </main>

    <footer>
        &copy; 2025 YADI SANG. 保留所有权利。
    </footer>
</body>
</html>
