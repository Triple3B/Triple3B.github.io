<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Triple3B - Hồ Sơ Cá Nhân & Portfolio</title>
    <!-- Tải Tailwind CSS CDN để tạo kiểu dáng hiện đại và đáp ứng -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        /* Tùy chỉnh phong chữ và kiểu dáng cơ bản */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f7f9fb; /* Màu nền nhẹ nhàng */
        }
        .section-title {
            position: relative;
            display: inline-block;
            padding-bottom: 8px;
            margin-bottom: 30px;
        }
        .section-title::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 50%;
            height: 4px;
            background-color: #4f46e5; /* Màu tím Indigo */
            border-radius: 2px;
        }
        /* Hiệu ứng hover cho thẻ kỹ năng */
        .skill-tag {
            transition: all 0.2s ease-in-out;
        }
        .skill-tag:hover {
            transform: translateY(-2px) scale(1.05);
            box-shadow: 0 4px 15px rgba(79, 70, 229, 0.3); /* Shadow nhẹ nhàng hơn */
        }
    </style>
</head>
<body class="text-gray-800">

    <!-- Header & Giới Thiệu -->
    <header class="bg-indigo-600 shadow-xl text-white py-12 md:py-16">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col md:flex-row items-center">
            <!-- Ảnh Đại Diện (Placeholder) -->
            <div class="w-32 h-32 md:w-40 md:h-40 bg-white rounded-full p-1 ring-4 ring-indigo-300 mb-6 md:mb-0 md:mr-8">
                <img class="w-full h-full object-cover rounded-full" 
                     src="https://placehold.co/160x160/3730a3/ffffff?text=3B" 
                     alt="Ảnh đại diện Triple3B">
            </div>
            
            <!-- Thông Tin Cơ Bản -->
            <div>
                <h1 class="text-4xl md:text-5xl font-extrabold mb-1">TRIPLE3B</h1>
                <p class="text-xl md:text-2xl font-light text-indigo-200">Kỹ Sư Phát Triển Web | Lập Trình Viên Full-stack</p>
                <div class="mt-4 flex space-x-4">
                    <!-- Các icon liên kết -->
                    <a href="https://github.com/Triple3B" target="_blank" class="text-indigo-200 hover:text-white transition duration-200">
                        <!-- Icon GitHub (SVG) -->
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path fill-rule="evenodd" d="M12 2C6.477 2 2 6.484 2 12.017c0 4.417 2.865 8.16 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.823-.012-1.624-2.784.602-3.37-.269-3.37-.269-.454-1.156-1.11-1.46-1.11-1.46-.908-.619.069-.607.069-.607 1.004.072 1.531 1.032 1.531 1.032.892 1.524 2.341 1.084 2.903.829.091-.643.35-1.084.634-1.332-2.22-.251-4.555-1.118-4.555-4.957 0-1.096.39-1.996 1.029-2.701-.103-.255-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.025A9.228 9.228 0 0112 6.836c.92.007 1.848.12 2.72.355 1.909-1.295 2.748-1.025 2.748-1.025.542 1.378.199 2.395.099 2.65.64.705 1.029 1.605 1.029 2.701 0 3.84-2.339 4.702-4.562 4.949.359.31.678.921.678 1.855 0 1.337-.012 2.418-.012 2.741 0 .268.18.583.687.483C20.141 20.177 23 16.434 23 12.017 23 6.484 18.522 2 13 2z" clip-rule="evenodd" /></svg>
                    </a>
                    <a href="mailto:email@example.com" class="text-indigo-200 hover:text-white transition duration-200">
                        <!-- Icon Email (SVG) -->
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8m-2 8a2 2 0 01-2 2H7a2 2 0 01-2-2V6a2 2 0 012-2h10a2 2 0 012 2v10z"></path></svg>
                    </a>
                </div>
            </div>
        </div>
    </header>

    <main class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 py-12">

        <!-- Giới Thiệu Bản Thân -->
        <section class="mb-12 p-6 bg-white rounded-xl shadow-lg">
            <h2 class="section-title text-2xl font-bold text-gray-800">Giới Thiệu</h2>
            <p class="text-gray-600 leading-relaxed">
                Tôi là **Triple3B**, một Kỹ sư phần mềm đam mê tạo ra các giải pháp web hiệu suất cao và có trải nghiệm người dùng tuyệt vời. Tôi có kinh nghiệm làm việc với các công nghệ Frontend và Backend hiện đại, đặc biệt là trong việc xây dựng các ứng dụng dựa trên dữ liệu. Mục tiêu của tôi là biến những ý tưởng phức tạp thành các sản phẩm kỹ thuật số đơn giản và dễ tiếp cận.
            </p>
        </section>

        <!-- Kỹ Năng -->
        <section class="mb-12 p-6 bg-white rounded-xl shadow-lg">
            <h2 class="section-title text-2xl font-bold text-gray-800">Kỹ Năng Kỹ Thuật</h2>
            <div class="flex flex-wrap gap-3">
                <!-- Frontend -->
                <span class="skill-tag bg-blue-500 text-white text-sm font-semibold px-4 py-2 rounded-full">HTML & CSS (Tailwind)</span>
                <span class="skill-tag bg-yellow-500 text-gray-900 text-sm font-semibold px-4 py-2 rounded-full">JavaScript (ES6+)</span>
                <span class="skill-tag bg-sky-500 text-white text-sm font-semibold px-4 py-2 rounded-full">ReactJS / Angular</span>
                
                <!-- Backend & Database -->
                <span class="skill-tag bg-green-600 text-white text-sm font-semibold px-4 py-2 rounded-full">Node.js (Express)</span>
                <span class="skill-tag bg-gray-700 text-white text-sm font-semibold px-4 py-2 rounded-full">Python (Django/Flask)</span>
                <span class="skill-tag bg-orange-600 text-white text-sm font-semibold px-4 py-2 rounded-full">Firebase / Firestore</span>
                <span class="skill-tag bg-indigo-500 text-white text-sm font-semibold px-4 py-2 rounded-full">SQL & MongoDB</span>
                
                <!-- Công cụ -->
                <span class="skill-tag bg-red-700 text-white text-sm font-semibold px-4 py-2 rounded-full">Git & GitHub Pages</span>
                <span class="skill-tag bg-pink-500 text-white text-sm font-semibold px-4 py-2 rounded-full">AWS/Vercel Deployment</span>
            </div>
        </section>

        <!-- Dự Án Nổi Bật (Thẻ dự án mẫu) -->
        <section class="mb-12 p-6 bg-white rounded-xl shadow-lg">
            <h2 class="section-title text-2xl font-bold text-gray-800">Dự Án Nổi Bật</h2>
            <div class="grid md:grid-cols-2 gap-6">
                <!-- Dự án 1 -->
                <div class="border border-gray-200 p-5 rounded-lg hover:shadow-xl transition duration-300">
                    <h3 class="text-xl font-bold mb-2 text-indigo-700">1. Ứng Dụng Quản Lý Công Việc (ToDo App)</h3>
                    <p class="text-gray-600 mb-3 text-sm">Xây dựng bằng React và sử dụng Firebase Firestore để lưu trữ dữ liệu thời gian thực. Hỗ trợ đăng nhập và đồng bộ hóa đa thiết bị.</p>
                    <div class="flex gap-2 mb-3">
                        <span class="bg-purple-100 text-purple-800 text-xs px-3 py-1 rounded-full">React</span>
                        <span class="bg-red-100 text-red-800 text-xs px-3 py-1 rounded-full">Firestore</span>
                        <span class="bg-gray-100 text-gray-800 text-xs px-3 py-1 rounded-full">Tailwind CSS</span>
                    </div>
                    <a href="#" target="_blank" class="text-indigo-600 hover:text-indigo-800 font-medium">
                        Xem Dự Án &rarr;
                    </a>
                </div>

                <!-- Dự án 2 -->
                <div class="border border-gray-200 p-5 rounded-lg hover:shadow-xl transition duration-300">
                    <h3 class="text-xl font-bold mb-2 text-indigo-700">2. Blog Cá Nhân Tĩnh</h3>
                    <p class="text-gray-600 mb-3 text-sm">Sử dụng Jekyll (hoặc Hugo) và Markdown để tạo blog cá nhân. Tối ưu hóa SEO và tốc độ tải trang cực nhanh nhờ GitHub Pages.</p>
                    <div class="flex gap-2 mb-3">
                        <span class="bg-teal-100 text-teal-800 text-xs px-3 py-1 rounded-full">Jekyll</span>
                        <span class="bg-teal-100 text-teal-800 text-xs px-3 py-1 rounded-full">Markdown</span>
                        <span class="bg-gray-100 text-gray-800 text-xs px-3 py-1 rounded-full">GitHub Pages</span>
                    </div>
                    <a href="#" target="_blank" class="text-indigo-600 hover:text-indigo-800 font-medium">
                        Xem Blog &rarr;
                    </a>
                </div>
            </div>
        </section>

        <!-- Kinh Nghiệm (Placeholder) -->
        <section class="mb-12 p-6 bg-white rounded-xl shadow-lg">
            <h2 class="section-title text-2xl font-bold text-gray-800">Kinh Nghiệm & Giáo Dục</h2>
            <div class="space-y-6">
                <!-- Kinh nghiệm 1 -->
                <div>
                    <h3 class="text-xl font-semibold text-gray-700">Kỹ Sư Phát Triển Phần Mềm</h3>
                    <p class="text-indigo-600 font-medium">Công ty XYZ - 2022 đến Hiện tại</p>
                    <ul class="list-disc list-inside text-gray-600 ml-4 mt-1 text-sm">
                        <li>Phát triển và bảo trì các tính năng Frontend chính bằng ReactJS.</li>
                        <li>Tối ưu hóa hiệu suất trang web, giảm thời gian tải trung bình 30%.</li>
                    </ul>
                </div>
                <!-- Giáo dục -->
                <div>
                    <h3 class="text-xl font-semibold text-gray-700">Cử Nhân Công Nghệ Thông Tin</h3>
                    <p class="text-indigo-600 font-medium">Đại Học Bách Khoa - 2018 đến 2022</p>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-6">
        <div class="max-w-4xl mx-auto text-center px-4">
            <p class="text-sm">&copy; 2025 Triple3B. Được xây dựng và triển khai bằng GitHub Pages.</p>
        </div>
    </footer>

    <script>
        // JavaScript tối thiểu, ví dụ cho việc tương tác sau này.
        console.log("Hồ sơ của Triple3B đã tải thành công.");
    </script>

</body>
</html>

