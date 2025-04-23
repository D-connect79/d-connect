<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="initial-scale=1.0">
    <meta name="description" content="D-Connect cung cấp eSIM và thẻ SIM 4G tốc độ cao cho người Việt tại Nhật Bản">
    <meta name="keywords" content="D-Connect, eSIM, thẻ SIM, dữ liệu 4G, người Việt tại Nhật">
    <title>D-Connect - eSIM & Thẻ SIM 4G cho Người Việt tại Nhật</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
        }
        .hero-bg {
            background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e');
            background-size: cover;
            background-position: center;
        }
        .plan-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .plan-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px rgba(0, 0, 0, 0.1);
        }
        ul li {
            position: relative;
            padding-left: 1.5rem;
        }
        ul li:before {
            content: '✔';
            position: absolute;
            left: 0;
            color: #FFD700; /* Vàng */
        }
    </style>
</head>
<body class="bg-gray-100">
    <!-- Header -->
    <header class="bg-gray-800 text-white sticky top-0 z-10 shadow-md">
        <nav class="container mx-auto flex justify-between items-center py-4 px-6">
            <div class="text-2xl font-bold flex items-center">
                <img src="/image" alt="" class="h-8 mr-2"> D-Connect
            </div>
            <ul class="flex space-x-6">
                <li><a href="#home" class="hover:text-yellow-300" aria-label="Đi đến trang chủ">Trang chủ</a></li>
                <li><a href="#plans" class="hover:text-yellow-300" aria-label="Đi đến gói dữ liệu">Gói dữ liệu</a></li>
                <li><a href="#about" class="hover:text-yellow-300" aria-label="Đi đến giới thiệu">Giới thiệu</a></li>
                <li><a href="#contact" class="hover:text-yellow-300" aria-label="Đi đến liên hệ">Liên hệ</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero-bg text-white py-20">
        <div class="container mx-auto text-center">
            <h1 class="text-4xl md:text-5xl font-bold mb-4">D-Connect - Kết nối 4G cho Người Việt tại Nhật</h1>
            <p class="text-lg md:text-xl mb-6">Cung cấp eSIM và thẻ SIM 4G tốc độ cao, đáng tin cậy cho cộng đồng Việt Nam.</p>
            <div class="bg-yellow-100 text-gray-800 p-4 rounded-lg max-w-2xl mx-auto mb-6">
                <p>Chỉ từ ¥1,150 cho gói 10 ngày không giới hạn dữ liệu, D-Connect mang đến kết nối nhanh chóng và quy trình kích hoạt đơn giản. Liên hệ ngay để được tư vấn gói phù hợp!</p>
            </div>
            <a href="#plans" class="bg-yellow-500 text-black font-bold py-3 px-6 rounded-lg hover:bg-yellow-600">Khám phá gói dữ liệu</a>
        </div>
    </section>

    <!-- Plans Section -->
    <section id="plans" class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-12">Gói eSIM & Thẻ SIM 4G</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Plan 1 -->
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg text-center plan-card">
                    <h3 class="text-xl font-bold mb-4">Gói Tiết Kiệm</h3>
                    <p class="text-2xl font-bold mb-4">¥1,150</p>
                    <ul class="text-left mb-6">
                        <li class="mb-2">Dữ liệu 4G không giới hạn</li>
                        <li class="mb-2">Hiệu lực 10 ngày</li>
                        <li class="mb-2">Hỗ trợ eSIM & thẻ SIM</li>
                        <li class="mb-2">Mạng Softbank, PoVo</li>
                    </ul>
                    <button onclick="window.location.href='/checkout?plan=saving'" class="bg-gray-800 text-white py-2 px-4 rounded hover:bg-gray-900">Mua ngay</button>
                </div>
                <!-- Plan 2 -->
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg text-center plan-card">
                    <h3 class="text-xl font-bold mb-4">Gói Phổ Thông</h3>
                    <p class="text-2xl font-bold mb-4">¥2,250</p>
                    <ul class="text-left mb-6">
                        <li class="mb-2">Dữ liệu 4G không giới hạn</li>
                        <li class="mb-2">Hiệu lực 20 ngày</li>
                        <li class="mb-2">Hỗ trợ eSIM & thẻ SIM</li>
                        <li class="mb-2">Mạng Softbank, PoVo</li>
                    </ul>
                    <button onclick="window.location.href='/checkout?plan=standard'" class="bg-gray-800 text-white py-2 px-4 rounded hover:bg-gray-900">Mua ngay</button>
                </div>
                <!-- Plan 3 -->
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg text-center plan-card">
                    <h3 class="text-xl font-bold mb-4">Gói Không Giới Hạn</h3>
                    <p class="text-2xl font-bold mb-4">¥2,980</p>
                    <ul class="text-left mb-6">
                        <li class="mb-2">Dữ liệu 4G không giới hạn</li>
                        <li class="mb-2">Hiệu lực 30 ngày</li>
                        <li class="mb-2">Hỗ trợ eSIM & thẻ SIM</li>
                        <li class="mb-2">Mạng Softbank, PoVo</li>
                    </ul>
                    <button onclick="window.location.href='/checkout?plan=unlimited'" class="bg-gray-800 text-white py-2 px-4 rounded hover:bg-gray-900">Mua ngay</button>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 bg-gray-100">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-12">Về D-Connect</h2>
            <p class="text-lg text-center max-w-3xl mx-auto">D-Connect là thương hiệu cung cấp eSIM và thẻ SIM 4G dành riêng cho người Việt tại Nhật Bản. Hợp tác với Softbank và PoVo, chúng tôi mang đến kết nối tốc độ cao và quy trình đặt hàng đơn giản. Hỗ trợ các anh chị em đang dùng SIM nghe gọi và dung lượng internet không đủ dùng, liên hệ ngay cho D-Connect để được tư vấn cụ thể!</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-12">Liên hệ với D-Connect</h2>
            <div class="max-w-lg mx-auto">
                <form id="contact-form" class="space-y-6">
                    <div>
                        <label for="name" class="block text-sm font-medium text-gray-700">Họ và tên</label>
                        <input type="text" id="name" class="mt-1 block w-full p-2 border border-gray-300 rounded-md" required>
                    </div>
                    <div>
                        <label for="email" class="block text-sm font-medium text-gray-700">Email</label>
                        <input type="email" id="email" class="mt-1 block w-full p-2 border border-gray-300 rounded-md" required>
                    </div>
                    <div>
                        <label for="message" class="block text-sm font-medium text-gray-700">Tin nhắn</label>
                        <textarea id="message" rows="4" class="mt-1 block w-full p-2 border border-gray-300 rounded-md" required></textarea>
                    </div>
                    <button type="submit" class="bg-gray-800 text-white py-2 px-4 rounded hover:bg-gray-900">Gửi</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-6">
        <div class="container mx-auto text-center">
            <p>© 2025 D-Connect. All rights reserved.</p>
            <p class="mt-2">Email: support@d-connect.jp | Phone: +81-070-8976-1617</p>
            <p class="mt-2">
                <a href="https://linkedin.com" class="text-yellow-300 hover:underline">LinkedIn</a> |
                <a href="https://facebook.com" class="text-yellow-300 hover:underline">Facebook</a>
            </p>
        </div>
    </footer>

    <script>
        // Form validation and submission
        document.getElementById('contact-form').addEventListener('submit', function(e) {
            e.preventDefault();
            const email = document.getElementById('email').value;
            const name = document.getElementById('name').value;
            const message = document.getElementById('message').value;

            if (!email.match(/^\S+@\S+\.\S+$/)) {
                alert('Vui lòng nhập email hợp lệ.');
                return;
            }
            if (name.trim().length < 2) {
                alert('Họ và tên phải có ít nhất 2 ký tự.');
                return;
            }

            alert('Cảm ơn bạn đã liên hệ! Chúng tôi sẽ trả lời sớm nhất có thể.');
            this.reset();
        });

        // Smooth scrolling for navigation
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
