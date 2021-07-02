<h1>Project for "Phát triển ứng dụng web" - "UIT - VNUHCM"</h1>
Live Demo: https://truongtoi.koroko.dev


<h1>Thành viên tham gia</h1>
18520808: Phùng Thế Hùng <br>

<h1>Hướng dẫn cài trên localhost</h1>

<h2>Chuẩn bị</h2>
<ul>
    <li>Composer</li>
    <li>NodeJS (dùng để cài đặt gói)</li>
    <li>Apache Http Server (có thể dùng Wamp, Xamp hoặc Laragon)</li>
</ul>


<h2>Tiến hành các bước</h2>

<ul>
    <li>Bước 1: Git clone dự án về máy, sau đó cd tới đường dẫn của bạn</li>
    <li>Bước 2: Cài các gói composer) <br> Bạn vào cmd, gõ câu lệnh sau: composer install và chờ các gói được cài đặt xong</li>
    <li>Apache Http Server (có thể dùng Wamp, Xamp hoặc Laragon)</li>
    <li>Bước 3: Cài các gói npm<br>Gõ câu lệnh sau: npm install và chờ các gói được cài đặt xong</li>
    <li>Bước 4: Tạo key<br>
Gõ câu lệnh sau php artisan key:generate</li>
    <li>Bước 5: Tạo database<br>
Gõ php artisan migrate để laravel đồng bộ với db và tạo sẵn table</li>
    <li>Bước 6: Chạy<br>Trước khi chạy, cần phải mở WAMP, XAMP hoặc gì đó để bật Apache server, sau đó gõ php artisan serve. Web sẽ nằm trên localhost:8000.</li>
</ul>








