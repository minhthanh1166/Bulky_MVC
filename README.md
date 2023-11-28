<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cửa hàng sách Bulky Book</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f2f2f2;
        }

        header {
            text-align: center;
            padding: 2em;
            background-color: #333;
            color: white;
        }

        section {
            padding: 2em;
        }

        .project-intro {
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 2em;
            margin-bottom: 2em;
        }

        .project-intro h1 {
            font-size: 2em;
            color: #333;
        }

        .project-description {
            font-size: 1.2em;
            color: #555;
        }

        .team-members {
            margin-top: 2em;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 1em;
        }

        th, td {
            padding: 1em;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }

        th {
            background-color: #333;
            color: white;
        }

        .project-features {
            background-color: #f9f9f9;
            padding: 2em;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .feature-list {
            list-style-type: none;
            padding: 0;
        }

        .feature-list li {
            margin-bottom: 1em;
        }

        .footer {
            text-align: center;
            background-color: #333;
            color: white;
            padding: 1em;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <h1>Cửa hàng sách Bulky Book</h1>
    </header>

    <section class="project-intro">
        <h1>Chào mừng bạn đến với dự án Bulky Book!</h1>
        <p class="project-description">
            Xây dựng trang web mua sắm sách độc đáo với những tính năng hiện đại và thuận tiện cho người dùng. Hãy khám phá những điều tuyệt vời mà chúng tôi đã mang đến!
        </p>
        <div class="team-members">
            <h2>Thành viên trong dự án</h2>
            <table>
                <tr>
                    <th>STT</th>
                    <th>Họ tên</th>
                    <th>Nhiệm vụ</th>
                    <th>Đóng góp</th>
                </tr>
                <tr>
                    <td>1</td>
                    <td>Bùi Minh Thành</td>
                    <td>FrontEnd, Backend, Thiết kế usecase, ERD</td>
                    <td>100%</td>
                </tr>
            </table>
        </div>
    </section>

    <section class="project-features">
        <h2>Những tính năng nổi bật</h2>
        <ul class="feature-list">
            <li>Sử dụng identity để đăng nhập và phân quyền, hỗ trợ đăng nhập từ Facebook, Microsoft.</li>
            <li>Tích hợp bảo mật 2 lớp cho tài khoản khách hàng.</li>
            <li>Thanh toán linh hoạt với Stripe.</li>
            <li>Quản lý đơn hàng và theo dõi thời gian giao hàng.</li>
            <li>Trang quản trị Admin với nhiều tính năng quản lý doanh nghiệp.</li>
            <li>Quản lý sản phẩm hiệu quả với Entity Framework.</li>
        </ul>
    </section>

    <footer class="footer">
        &copy; 2023 Cửa hàng sách Bulky Book. All rights reserved.
    </footer>

</body>
</html>
