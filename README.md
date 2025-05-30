# FAMOUS
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>比较有名的人导航页</title>
    <!-- Font Awesome 图标库 -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            line-height: 1.6;
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
            background: #f8f9fa;
        }

        .container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(160px, 1fr));
            gap: 15px;
            padding: 20px;
        }

        .card {
            background: white;
            border-radius: 10px;
            padding: 15px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            transition: transform 0.2s;
        }

        .card:hover {
            transform: translateY(-3px);
        }

        .card a {
            text-decoration: none;
            color: #333;
        }

        .icon {
            font-size: 24px;
            margin-bottom: 10px;
            color: #2c3e50;
        }

        .site-name {
            font-size: 14px;
            word-break: break-all;
        }

        @media (max-width: 600px) {
            .container {
                grid-template-columns: repeat(auto-fill, minmax(120px, 1fr));
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- 示例链接（按需修改） -->
        <div class="card">
            <a href="https://www.zhihu.com/" target="_blank">
                <i class="fas fa-envelope icon"></i>
                <div class="site-name">知乎</div>
            </a>
        </div>

        <div class="card">
            <a href="http://images.newsmth.net/nForum/#!mainpage" target="_blank">
                <i class="fab fa-github icon"></i>
                <div class="site-name">水木社区</div>
            </a>
        </div>
    </div>
</body>
</html>
