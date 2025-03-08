<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>파일이 삭제되었습니다.</title>
    <style>
        body {
            background-color: black;
            color: white;
            font-family: 'Courier New', monospace;
            text-align: center;
            padding: 50px;
        }
        .glitch {
            font-size: 24px;
            font-weight: bold;
            color: #ff0000;
            text-shadow: 2px 2px 5px rgba(255, 0, 0, 0.5);
            animation: glitch 1.5s infinite;
        }
        @keyframes glitch {
            0% { opacity: 1; }
            20% { opacity: 0.8; transform: translate(1px, 1px); }
            40% { opacity: 1; transform: translate(-1px, -1px); }
            60% { opacity: 0.8; transform: translate(2px, -2px); }
            80% { opacity: 1; transform: translate(-2px, 2px); }
            100% { opacity: 1; }
        }
        .hidden-message {
            font-size: 16px;
            color: #666;
            opacity: 0;
            transition: opacity 3s ease-in;
        }
        body:hover .hidden-message {
            opacity: 1;
        }
        .background-image {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://via.placeholder.com/800x600/000000/FFFFFF?text=루시아') no-repeat center center;
            background-size: cover;
            opacity: 0.02;
        }
    </style>
</head>
<body>
    <div class="background-image"></div>
    <h1 class="glitch">파일이 삭제되었습니다.</h1>
    <p class="hidden-message">너는 여기 오면 안 됐다.</p>
</body>
</html>
