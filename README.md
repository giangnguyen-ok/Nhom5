<html lang="en">
<head>
‹style>
•rainbow-text {
color: white; /* Màu chữ ban đầu */
-webkit-text-stroke: 1px black; /* Viền chữ màu đen */
animation: rainbow 3s infinite;
}
</style>
</head> <head>
‹meta charset="UTF-8">
<meta name="viewport"
content="width=device-width, initial-scale=1.0">
‹ title>Pano Đầu Trang</title>
<!-- Thêm font chữ Poppins từ
Google Fonts -->
<link
href="https://fonts.googleapis.com
/css2? family=Poppins:wght@400;700&displa y=swap" rel="stylesheet">
‹style>
/* Reset cơ bản */
body {
margin: 0; font-family:
'Poppins', sans-serif; /* Đổi font chữ sang Poppins */

}
/* Pano đầu trang */
•header-banner { background-color:
#fF99cc; /* Màu hồng pastel */
height: 300px; display: flex;
justify-content:
center;
chữ xám đậm */
align-items: center; text-align: center;
color: #4a4a4a; /* Màu
position: relative; overflow: hidden;

}
/* Nội dung trong pano */
•banner-content h1 { font-size: 3rem; /*
Đổi kích thước chữ */
margin: 0; font-weight: 700;
text-transform:
uppercase; /* Viết hoa toàn bộ */
animation: slideIn 3s
ease-in-out infinite; /* Thêm hiệu ứng chuyển động */
｝
•banner-content p {
font-size: 1.2rem; margin-top: 10px; font-style: italic; /*Chữ in nghiêng */

color: #ffffff; /* Màu
chữ trắng */ animation: fadeIn 5s
ease-in-out infinite; /* Thêm hiệu ứng chuyển động cho đoạn văn */
}
/* Hiệu ứng chuyển động
cho tiêu đề */
@keyframes slideIn {
0% {
translateX(-100%) ;
}
50% {
transform:
opacity: 0;
transform:
translateX(0);
}
100% {
opacity: 1;
transform:
translateX(100%) ; opacity: 0;
/* Hiệu ứng chuyển động
cho đoạn văn */
@keyframes fadeIn {
0% { opacity: 0;
}
50% < opacity: 1;
}
100% { opacity: 0;
｝
</style>
</head> ‹body>
<! -- Pano đầu trang --> <header class="header-banner" > <div class="banner-
content" > <h1> Chào mừng đến với
Website của nhóm 5 lớp 12 Lý</h1>
<p>Nơi để chúng mình
chia sẻ về bản thân</p>
</div›
</header>
</body>
 </html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chữ bên trái, Hình ảnh bên phải</title>
    <style>
        /* Thiết lập nền trang màu xanh dương nhạt */
        body {
            background-color: #a0c4ff; /* Màu xanh dương nhạt */
            margin: 0;
            font-family: Arial, sans-serif;
        }

        /* Container chính chứa chữ và hình ảnh */
        .container {
            display: flex;
            flex-direction: column;
            padding: 20px;
        }

        /* Cả hai phần chữ và hình ảnh đều được căn chỉnh hợp lý */
        .row {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 40px; /* Tạo khoảng cách giữa các phần */
        }

        /* Đảm bảo chữ bên trái luôn căn lề trái */
        .text {
            flex: 1; /* Phần chữ chiếm không gian còn lại */
            padding: 20px;
            color: #333;
        }

        /* Đảm bảo hình ảnh bên phải luôn căn lề phải */
        .image {
            flex: 1; /* Phần hình ảnh chiếm không gian còn lại */
            text-align: right; /* Căn phải hình ảnh */
        }

        /* Thiết lập kích thước và tạo một chút hiệu ứng cho hình ảnh */
        .image img {
            max-width: 100%; /* Hình ảnh sẽ chiếm hết chiều rộng của container */
            height: auto;
            border-radius: 8px; /* Tạo góc bo tròn cho hình ảnh */
        }

        /* Thiết lập chữ trong phần .text */
        .text h1 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }

        .text p {
            font-size: 1.2rem;
            line-height: 1.6;
        }

        /* Đảo ngược vị trí của chữ và hình ảnh trong phần reverse */
        .reverse {
            flex-direction: row-reverse;
        }

        /* Thiết lập bảng nếu có */
        table {
            width: 100%;
            margin-top: 20px;
            border-collapse: collapse;
        }

        table, th, td {
            border: 1px solid #ddd;
        }

        th, td {
            padding: 10px;
            text-align: center;
        }
    </style>
</head>
<body>

   <!-- Container chứa các phần tử chữ và hình ảnh -->
    <div class="container">
        <!-- Lần 1: Chữ trái, ảnh phải -->
        <div class="row">
            <div class="text">
                <h1>Chào mừng đến với trang web của chị em chúng mình</h1>
                <p> Xin chào mọi người, tụi mình là nhóm 5. Nhóm tụi mình gồm 5 thành viên: Trường Giang, Hồng Ngọc, Hùng Dinh, Ngọc Thịnh, Phú Quý. Hiện tại Phú Quý đang học đội tuyển nên tạm thời 4 đứa mình sẽ cùng làm thay phần của Phú Quý</p>
            </div>
            <div class="image">
                <img src="hinfh nhoms.jpg" alt="Nhóm 5">
            </div>
        </div>

        <!-- Lần 2: Chữ phải, ảnh trái -->
        <div class="row reverse">
            <div class="text">
                <h1>Slogan nhóm chúng mình</h1>
                <p>Chúng mình rất tâm đắc với slogan này, nó đề cao tầm quan trọng của thái độ mỗi người</p>
            </div>
            <div class="image">
                <img src="z6098511130906_41c8d16fc0220dc4c1cbf0771a0de042.jpg" alt="Slogan nhóm">
            </div>
        </div>

        <!-- Lần 3: Chữ trái, ảnh phải -->
        <div class="row">
            <div class="text">
                <h1>Thành viên nhóm 5</h1>
                <p>Nhấn vào tên từng người để tìm hiểu kĩ hơn về người đó nhé.</p>
            </div>
            <div class="image">
                <table>
                    <tr>
                        <th>Họ và tên</th>
                    </tr>
                    <tr>
                        <td><a href="https://giangnguyen-ok.github.io/profilengocthinh.github.io/">Ngọc Thịnh</a></td>
                    </tr>
                    <tr>
                        <td><a href="https://giangnguyen-ok.github.io/profilehongngoc.github.io/">Hồng Ngọc</a></td>
                    </tr>
                    <tr>
                        <td><a href="https://giangnguyen-ok.github.io/profilephuquy.github.io/">Phú Quý</a></td>
                    </tr>
                    <tr>
                        <td><a href="https://giangnguyen-ok.github.io/profilegiang.github.io/">Trường Giang</a></td>
                    </tr>
                    <tr>
                        <td><a href="https://giangnguyen-ok.github.io/profilehungdinh.github.io/">Hùng Dinh</a></td>
                    </tr>
                </table>
            </div>
        </div>

        <!-- Lần 4: Chữ phải, ảnh trái -->
        <div class="row reverse">
            <div class="text">
                <h1>Giới thiệu web học tập</h1>
                <p>Giới thiệu web học tập, hãy <a href="https://www.vietjack.com/">click vào đây</a>.</p>
                <p>Giới thiệu link canva , hãy <a href="https://www.canva.com/design/DAGWSFUgBIc/2qh19OgTTBR9hlcWDLbu7A/edit?fbclid=IwZXh0bgNhZW0CMTEAAR12UuPckurqTYYRCniLnM98Jb9QwE0k5mXx068pr1BKQIQ34rU9iZj1vmI_aem_IJLm5NA5tlObgczUDO-n7w">click vào đây</a>.</p>
            </div>
            <div class="image">
                <img src="unnamed.png" alt="Giới thiệu web học tập">
            </div>
        </div>
    </div>

    <p>Giới thiệu bản thân các bạn cho tụi mình biết với nhé hãy <a href="https://giangnguyen-ok.github.io/gioithieubanthan/">click vào đây</a>.</p>
</body>
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chào Xuân Mới</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>🌸 Chào Xuân Mới 2025 🌸</h1>
            <p>Xuân về mang đến niềm vui và hạnh phúc!</p>
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#about">Giới Thiệu</a></li>
            <li><a href="#wishes">Lời Chúc Tết</a></li>
            <li><a href="#traditions">Phong Tục Tết</a></li>
            <li><a href="#contact">Liên Hệ</a></li>
        </ul>
    </nav>

    <main>
        <section id="about" class="section">
            <h2>🌟 Về Tết Nguyên Đán</h2>
            <p class="highlight">
                Tết Nguyên Đán là dịp lễ truyền thống lớn nhất của người Việt, đánh dấu thời khắc chuyển giao năm cũ và năm mới.
            </p>
            <p>Thời gian này là lúc mọi người sum vầy bên gia đình, tưởng nhớ tổ tiên, và gửi những lời chúc tốt đẹp nhất đến người thân yêu.</p>
        </section>

        <section id="wishes" class="section">
            <h2>💌 Lời Chúc Tết Hay Nhất</h2>
            <div class="wish-box">
                <p id="p1">✨ Chúc năm mới sức khỏe dồi dào, vạn sự như ý!</p>
                <p class="highlight">🍀 Chúc bạn và gia đình an khang, thịnh vượng, hạnh phúc viên mãn.</p>
                <p class="highlight">🎉 Năm mới đến, chúc phát tài phát lộc, công danh rạng rỡ!</p>
            </div>
        </section>

        <section id="traditions" class="section">
            <h2>🏮 Phong Tục Tết</h2>
            <ul>
                <li>Gói bánh chưng, bánh tét.</li>
                <li>Trang trí nhà cửa bằng hoa mai, hoa đào.</li>
                <li>Chúc Tết và lì xì trẻ nhỏ.</li>
                <li>Thờ cúng tổ tiên, cầu may mắn.</li>
            </ul>
        </section>
    </main>

    <footer id="contact">
        <p>📞 Liên hệ: <strong>0123 456 789</strong> | ✉️ Email: <strong>tetnguyendan@example.com</strong></p>
        <p>© 2025 - Thiết kế bởi bạn.</p>
    </footer>
</body>
</html>
