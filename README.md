# MOC SHOP -Website bán nhạc cụ
## CÁC CÔNG NGHỆ SỬ DỤNG

- **Front-End:** HTML, CSS, Javascript, [Bootstrap](https://getbootstrap.com/)
- **Back-End:** NodeJS(Express)
- **Database:** MongoDB
- **Khác:** [JWT](https://jwt.io/), [bcrypt](https://www.npmjs.com/package/bcrypt)
## CÁC CHỨC NĂNG CHÍNH

- CRUD danh mục, sản phẩm, nhân viên
- Xác thực, phân quyền người dùng
- Đổi mật khẩu, đặt lại mặt khẩu
- Tìm kiếm, live search, lọc sản phẩm
- Chức năng giỏ hàng, đặt hàng, thanh toán paypal
- Thống kê

## LINK DEPLOY
- Đang thực hiện:...
- Tài khoản trang Admin: (admin1@gmail.com/bao123456)

## Setup Local Development Enviroment

1. Clone dự án về local và trỏ đến thư mục

```
    https://github.com/bao2k1/moc-shop/
    cd moc-shop
```

2. Mở Terminal, cài đặt các Dependencies cho (admin/frontend/backend):

```
    npm install
```

3. Tạo file .env trong back end, tạo các biến môi trường như sau:
   
```
    PORT=5000
    JWT_SECRET=mocshop123
    NODE_ENV=development
    PAYPAL_CLIENT_ID=Ae46sStk6vVdgWwXZF64AYDqDnOJwMhfqSycQtuhXBJU7c3R5DuxhIVcKh_1Qi6r48S8jbwIJWX7Dq_j
    MONGO_URL=mongodb+srv://quangbao0205:adminshop123@cluster0.bgma3.mongodb.net/mocshopDataBase?retryWrites=true
```

4. Run

```
    npm start
```

6. Mở trình duyệt Web, truy cập localhost với port 3000

```
    localhost:3000
```

## Giao diện:


