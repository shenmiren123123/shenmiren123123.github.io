<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的个人网站</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f5f5f5;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            text-align: center;
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #4CAF50;
            font-weight: bold;
        }
        nav a:hover {
            color: #333;
        }
        main {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        footer {
            text-align: center;
            padding: 15px 0;
            background-color: #eee;
            margin-top: 40px;
            font-size: 14px;
            color: #666;
        }
    </style>
</head>
<body>
    <header>
        <h1>欢迎来到我的个人网站</h1>
        <p>分享我的学习、项目与生活</p>
    </header>

    <nav>
        <a href="#about">关于我</a>
        <a href="#projects">项目</a>
        <a href="#contact">联系我</a>
    </nav>

    <main>
        <section id="about">
            <h2>关于我</h2>
            <p>你好，我是 YADI SANG，一个热爱技术与创作的人。我喜欢写代码、搭建网站，也喜欢分享我的经验和知识。</p>
        </section>

        <section id="projects">
            <h2>项目展示</h2>
            <ul>
                <li>项目 1：个人博客</li>
                <li>项目 2：GitHub Pages 网站</li>
                <li>项目 3：小工具合集</li>
            </ul>
        </section>

        <section id="contact">
            <h2>联系我</h2>
            <p>可以通过邮箱联系我：<a href="mailto:youremail@example.com">youremail@example.com</a></p>
        </section>
    </main>

    <footer>
        &copy; 2025 YADI SANG. 保留所有权利。
    </footer>
</body>
</html>
