<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang Web Nhóm 5</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background-color: #a0c4ff;
        }

        .header-banner {
            background-color: #ff99cc;
            height: 300px;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: #4a4a4a;
            position: relative;
            overflow: hidden;
        }

        .banner-content h1 {
            font-size: 3rem;
            font-weight: 700;
            text-transform: uppercase;
            animation: slideIn 3s ease-in-out infinite;
        }

        .banner-content p {
            font-size: 1.2rem;
            font-style: italic;
            color: #ffffff;
            animation: fadeIn 5s ease-in-out infinite;
        }

        @keyframes slideIn {
            0% {
                transform: translateX(-100%);
                opacity: 0;
            }
            50% {
                transform: translateX(0);
                opacity: 1;
            }
            100% {
                transform: translateX(100%);
                opacity: 0;
            }
        }

        @keyframes fadeIn {
            0% {
                opacity: 0;
            }
            50% {
                opacity: 1;
            }
            100% {
                opacity: 0;
            }
        }

        .container {
            display: flex;
            flex-direction: column;
            padding: 20px;
        }

        .row {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 40px;
        }

        .text {
            flex: 1;
            padding: 20px;
            color: #333;
        }

        .image {
            flex: 1;
            text-align: right;
        }

        .image img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }

        .reverse {
            flex-direction: row-reverse;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        table, th, td {
            border: 1px solid #ddd;
        }

        th, td {
            padding: 10px;
            text-align: center;
        }

        .footer {
            text-align: center;
            padding: 20px;
            background-color: #ff99cc;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header class="header-banner">
        <div class="banner-content">
            <h1>Chào mừng đến với Website của nhóm 5 lớp 12 Lý</h1>
            <p>Nơi để chúng mình chia sẻ về bản thân</p>
        </div>
    </header>

    <div class="container">
        <div class="row">
            <div class="text">
                <h1>Chào mừng đến với trang web của nhóm 5</h1>
                <p>Nhóm tụi mình gồm 5 thành viên: Trường Giang, Hồng Ngọc, Hùng Dinh, Ngọc Thịnh, Phú Quý.</p>
            </div>
            <div class="image">
                <img src="hinfh_nhoms.jpg" alt="Nhóm 5">
            </div>
        </div>

        <div class="row reverse">
            <div class="text">
                <h1>Slogan nhóm chúng mình</h1>
                <p>Chúng mình rất tâm đắc với slogan này, nó đề cao tầm quan trọng của thái độ mỗi người.</p>
            </div>
            <div class="image">
                <img src="slogan.jpg" alt="Slogan nhóm">
            </div>
        </div>

        <div class="row">
            <div class="text">
                <h1>Thành viên nhóm 5</h1>
                <p>Nhấn vào tên từng người để tìm hiểu kĩ hơn về người đó.</p>
            </div>
            <div class="image">
                <table>
                    <tr><th>Họ và tên</th></tr>
                    <tr><td><a href="https://giangnguyen-ok.github.io/profilengocthinh.github.io/">Ngọc Thịnh</a></td></tr>
                    <tr><td><a href="https://giangnguyen-ok.github.io/profilehongngoc.github.io/">Hồng Ngọc</a></td></tr>
                    <tr><td><a href="https://giangnguyen-ok.github.io/profilephuquy.github.io/">Phú Quý</a></td></tr>
                    <tr><td><a href="https://giangnguyen-ok.github.io/profilegiang.github.io/">Trường Giang</a></td></tr>
                    <tr><td><a href="https://giangnguyen-ok.github.io/profilehungdinh.github.io/">Hùng Dinh</a></td></tr>
                </table>
            </div>
        </div>

        <div class="row reverse">
            <div class="text">
                <h1>Giới thiệu web học tập</h1>
                <p>Giới thiệu web học tập, hãy <a href="https://www.vietjack.com/">click vào đây</a>.</p>
                <p>Giới thiệu link Canva, hãy <a href="https://www.canva.com/design/DAGWSFUgBIc/">click vào đây</a>.</p>
            </div>
            <div class="image">
                <img src="learning.jpg" alt="Giới thiệu web học tập">
            </div>
        </div>
    </div>

    <div class="footer">
        <p>Giới thiệu bản thân các bạn cho tụi mình biết với nhé, hãy <a href="https://giangnguyen-ok.github.io/gioithieubanthan/">click vào đây</a>.</p>
        <p>Lời chúc Tết 2025 của nhóm 5 đến bạn, hãy <a href="https://giangnguyen-ok.github.io/TET2025.html.io/" title="Xem lời chúc Tết 2025">click vào đây</a>.</p>
    </div>
</body>
</html>
