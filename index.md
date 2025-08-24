<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>If Chong的个人网站</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f9f9f9;
        }
        
        h1 {
            color: #2c3e50;
            text-align: center;
            margin-bottom: 30px;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }
        
        h2 {
            color: #3498db;
            margin-top: 0;
        }
        
        .beige-box {
            width: 100%;
            background-color: #f5f5dc;
            border: 1px solid #e0e0e0;
            border-radius: 5px;
            padding: 20px;
            margin: 20px 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            box-sizing: border-box;
        }
        
        .content-section {
            background-color: white;
            padding: 15px;
            border-radius: 5px;
            margin-bottom: 20px;
            border-left: 4px solid #3498db;
        }
        
        ul, ol {
            padding-left: 20px;
            margin: 10px 0;
        }
        
        li {
            margin-bottom: 5px;
        }
        
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 15px 0;
        }
        
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        
        th {
            background-color: #3498db;
            color: white;
        }
        
        a {
            display: inline-block;
            color: #3498db;
            text-decoration: none;
            margin-top: 10px;
            padding: 8px 12px;
            border-radius: 4px;
            transition: background-color 0.3s;
        }
        
        a:hover {
            background-color: #e0e0e0;
            text-decoration: underline;
        }
        
        small {
            color: #7f8c8d;
        }
    </style>
</head>
<body>
    <h1>欢迎来到我的个人网站</h1>
    
    <div class="beige-box">
        <div class="content-section">
            <h2>小记</h2>
            <p>div (块级容器标签)</p >
            <p>h1~h6 (分级标题标签)</p >
            <p><strong><em><u>由外到内分别是：加粗、斜体、下划线</u></em></strong></p >
            <p><small>小文本格式</small></p >
            
            <div class="content-section">
                <p>列表示例：</p >
                <ul>
                    <li>无序列表项1</li>
                    <li>无序列表项2</li>
                </ul>
                <ol>
                    <li>有序列表项1</li>
                    <li>有序列表项2</li>
                </ol>
            </div>
            
            <div class="content-section">
                <p>表格示例：</p >
                <table>
                    <thead>
                        <tr>
                            <th>表头单元格</th>
                            <th>由外到内分别是：表格标签、表头定义、表格行、表头单元格</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>数据单元格1</td>
                            <td>数据内容1</td>
                        </tr>
                        <tr>
                            <td>数据单元格2</td>
                            <td>数据内容2</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
    </div>
    
    <div style="text-align: center; margin-top: 20px;">
    <p>跳转链接（测试用）</p>
        <a href=" ">肥猫的秘密基地（帝Ⅳ）</a >
    </div>
</body>
</html>
