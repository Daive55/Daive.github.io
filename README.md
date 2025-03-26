# Daive.github.io
这是我的第一个网站，欢迎光临
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>黄玺如的第一个网页</title>
    <style>
        /* 基础样式 */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: '微软雅黑', sans-serif;
            line-height: 1.6;
            background-color: #f0f2f5;
        }

        /* 导航栏 */
        .navbar {
            background: #333;
            color: white;
            padding: 1rem;
        }

        .navbar h1 {
            margin-left: 2rem;
        }

        /* 主要内容区域 */
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        /* 卡片样式 */
        .card {
            background: white;
            border-radius: 10px;
            padding: 2rem;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            margin-bottom: 2rem;
        }

        /* 按钮样式 */
        .btn {
            display: inline-block;
            padding: 0.8rem 1.5rem;
            background: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s;
        }

        .btn:hover {
            background: #0056b3;
        }

        /* 响应式设计 */
        @media (max-width: 768px) {
            .navbar h1 {
                font-size: 1.2rem;
                margin-left: 1rem;
            }
        }
    </style>
</head>
<body>
    <!-- 导航栏 -->
    <nav class="navbar">
        <h1>黄玺如大王的网站</h1>
    </nav>

    <!-- 主要内容 -->
    <div class="container">
        <div class="card">
            <h2>欢迎来到黄玺如的网页</h2>
            <p>这是一个响应式设计的现代网页示例，包含：</p>
            <ul>
                <li>导航栏</li>
                <li>卡片布局</li>
                <li>交互动画</li>
                <li>移动端适配</li>
            </ul>
            <button class="btn" onclick="showMessage()">点击对黄玺如进行成服</button>
            <p id="demo" style="margin-top: 1rem;"></p>
        </div>

        <div class="container">
            <!-- 第一个卡片保持不变... -->
    
            <!-- 修改后的图片卡片 -->
            <div class="card">
                <h3>黄玺如的偶像</h3>
                <img src="images/jaychou.jpg" 
                     alt="周杰伦宣传照" 
                     style="width: 100%; border-radius: 5px; margin: 1rem 0;">
                <p>帅炸天周杰伦照片</p>
            </div>
        </div>

    <script>
        // 简单交互功能
        function showMessage() {
            document.getElementById("demo").innerHTML = "🎉 玺如大王万岁！";
        }

        // 页面加载完成时执行
        window.onload = function() {
            console.log("页面加载完成");
        }
    </script>
</body>
</html>
