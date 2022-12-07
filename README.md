CÁC CÔNG NGHỆ SỬ DỤNG
Front-End: HTML, CSS, Javascript, Bootstrap
Back-End: NodeJS(Express)
Database: SQL(PostgreSQL)
Template Engine: EJS
Khác: Ckeditor, Chart.js, JWT, bcrypt, Cloudinary, csurf, nodemailer
CÁC CHỨC NĂNG CHÍNH
CRUD danh mục, sản phẩm, nhân viên
Xác thực, phân quyền người dùng
Đổi mật khẩu, đặt lại mặt khẩu
Lưu trữ ảnh trên Cloudinary
Tìm kiếm, live search (có sử dụng debounce), lọc sản phẩm
Chức năng giỏ hàng, đặt hàng
Thống kê
LINK DEPLOY
Website
Admin
Tài khoản nhân viên (nhanvien@gmail.com/123)
Setup Local Development Enviroment
Clone dự án về local và trỏ đến thư mục
    https://github.com/bao2k1/moc-shop
    cd moc-shop
Mở Terminal, cài đặt các Dependencies:
    npm install
Tạo file .env, tạo các biến môi trường như sau:

PORT=5000
JWT_SECRET=mocshop123
NODE_ENV=development
PAYPAL_CLIENT_ID=Ae46sStk6vVdgWwXZF64AYDqDnOJwMhfqSycQtuhXBJU7c3R5DuxhIVcKh_1Qi6r48S8jbwIJWX7Dq_j
MONGO_URL=mongodb+srv://quangbao0205:adminshop123@cluster0.bgma3.mongodb.net/mocshopDataBase?retryWrites=true

Run
    node index.js
Mở trình duyệt Web, truy cập localhost với port 3000
    localhost:3000
