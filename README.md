# AvailableAnimalFriend
An app that using AI to analyze your surrounding habitat to choose your available pet. It's include protect animal and give them a home.  




<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <title>Giải Cứu Động Vật</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }

        header {
            background-color: #2ecc71;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #27ae60;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 30px;
        }

        .animal-card {
            background: white;
            padding: 15px;
            margin: 15px 0;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .animal-card img {
            width: 200px;
            border-radius: 8px;
        }

        form {
            background: white;
            padding: 20px;
            border-radius: 8px;
        }

        input, textarea {
            width: 100%;
            padding: 8px;
            margin: 8px 0;
        }

        button {
            background-color: #2ecc71;
            color: white;
            padding: 10px 15px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }

        footer {
            background-color: #27ae60;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }
    </style>
</head>
<body>

<header>
    <h1>🐾 Trung Tâm Giải Cứu Động Vật</h1>
    <p>Chung tay cứu giúp những người bạn nhỏ</p>
</header>

<nav>
    <a href="#gioithieu">Giới thiệu</a>
    <a href="#danhsach">Động vật cần cứu</a>
    <a href="#dangky">Đăng ký nhận nuôi</a>
    <a href="#dangbai">Đăng bài giải cứu</a>
</nav>

<section id="gioithieu">
    <h2>💚 Về chúng tôi</h2>
    <p>Chúng tôi là tổ chức phi lợi nhuận chuyên giải cứu chó, mèo bị bỏ rơi và tìm mái ấm mới cho các bé.</p>
</section>

<section id="danhsach">
    <h2>🐶 Các bé đang chờ được nhận nuôi</h2>

    <div class="animal-card">
        <h3>Bé Mít</h3>
        <img src="https://placedog.net/400/300" alt="Dog">
        <p>Giống: Chó ta</p>
        <p>Tuổi: 1 năm</p>
        <p>Tính cách: Hiền lành, thân thiện</p>
    </div>

    <div class="animal-card">
        <h3>Bé Mun</h3>
        <img src="https://placekitten.com/400/300" alt="Cat">
        <p>Giống: Mèo đen</p>
        <p>Tuổi: 8 tháng</p>
        <p>Tính cách: Nghịch ngợm, dễ thương</p>
    </div>

</section>

<section id="dangky">
    <h2>📋 Đăng ký nhận nuôi</h2>

    <form>
        <label>Họ và tên:</label>
        <input type="text" required>

        <label>Số điện thoại:</label>
        <input type="tel" required>

        <label>Địa chỉ:</label>
        <input type="text" required>

        <label>Lý do muốn nhận nuôi:</label>
        <textarea rows="4"></textarea>

        <button type="submit">Gửi đăng ký</button>
    </form>
</section>

<section id="dangbai">
    <h2>📝 Đăng bài giải cứu</h2>
    <form>
        <label>Tên bài viết:</label>
        <input type="text" required>

        <label>Nội dung bài giải cứu:</label>
        <textarea rows="5" required></textarea>

        <button type="submit">Gửi bài</button>
    </form>
</section>

<footer>
    <p>📞 Liên hệ: 0928 099 613 | 📧 votrantuankiet10082007@gmail.com</p>
    <p>© 2026 Trung Tâm Giải Cứu Động Vật</p>
</footer>

</body>
</html>
