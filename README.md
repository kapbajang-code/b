# b
가자
[index.html](https://github.com/user-attachments/files/26208110/index.html)
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Link Tree</title>
    <style>
        body {
            font-family: 'Apple SD Gothic Neo', sans-serif;
            background-color: #f0f2f5;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            margin: 0;
        }

        .container {
            width: 90%;
            max-width: 400px;
            text-align: center;
        }

        h1 {
            color: #333;
            margin-bottom: 30px;
        }

        .link-box {
            display: block;
            background-color: #ffffff;
            color: #333;
            text-decoration: none;
            margin-bottom: 15px;
            padding: 20px;
            border-radius: 12px;
            font-weight: bold;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            transition: transform 0.2s, background-color 0.2s;
        }

        /* 마우스를 올렸을 때 효과 */
        .link-box:hover {
            transform: translateY(-3px);
            background-color: #e9ecef;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>나의 링크 리스트</h1>

        <a href="https://lite.tiktok.com/t/ZS9RLArxRm3xY-PAzix/" class="link-box">1번 링크 바로가기</a>
        <a href="https://www.naver.com" class="link-box">2번 링크 바로가기</a>
        <a href="#" class="link-box">3번 링크 바로가기</a>
        <a href="#" class="link-box">4번 링크 바로가기</a>
        <a href="#" class="link-box">5번 링크 바로가기</a>
    </div>

</body>
</html>
