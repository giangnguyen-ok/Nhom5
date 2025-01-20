
<html lang="en">
<head> 
    <style>
         .rainbow-text {
            color: white; /* Màu chữ ban đầu */
            -webkit-text-stroke: 1px black; /* Viền chữ màu đen */
            animation: rainbow 3s infinite;
        }
    </style>
</head>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-w6s ease-in-out infinite; /* Thêm hiệu ứng chuyển động */
        }

        .banner-content p {
            font-size: 1.2rem;
            margin-top: 10px;
            font-style: italic; /* Chữ in nghiêng */
            color: #ffffff; /* Màu chữ trắng */
            animation: fadeIn 10s ease-in-out infinite; /* Thêm hiệu ứng chuyển động cho đoạn văn */
        }

        /* Hiệu ứng chuyển động cho tiêu đề */
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

        /* Hiệu ứng chuyển động cho đoạn văn */
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
    </style>
</head>
<body>

    <!-- Pano đầu trang -->
    <header class="header-banner">
        <div class="banner-content">
            <h1>Chào mừng đến với Website của nhóm 5 lớp 12 Lý</h1>
            <p>Nơi để chúng mình chia sẻ về bản thân</p>
        </div>
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
