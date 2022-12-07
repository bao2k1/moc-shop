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

- Trang chủ:
    ![]
  (https://res.cloudinary.com/dbynglvwk/image/upload/v1654943598/ie213/Capture2_kyv3k0.png)
- Trang lọc sản phẩm
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1654943598/ie213/Capture3_tpgikm.png)
- Trang chi tiết sản phẩm
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1654943597/ie213/Capture4_zcfctj.png)
- Tìm kiếm sản phẩm
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1655466125/ie213/Capture3_lmbywi.png)
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1654943597/ie213/Capture5_oc1d63.png)

- Xác thực người dùng
    - Đăng nhập
    - Đăng nhập với Google
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1654943920/ie213/Capture6_ddfeec.png)
    - Đăng nhập với Facebook
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1654943920/ie213/Capture7_pe2szd.png)


- Chức năng giỏ hàng, đặt hàng, thanh toán
    - Trang giỏ hàng
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1655350339/ie213/Capture1_swjonr.png)
    - Trang đặt hàng
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1655350339/ie213/Capture2_vlwjq0.png)
    - Sau khi đặt hàng thành công
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1655350339/ie213/Capture3_orrx37.png)
    - Thanh toán qua PayPal
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1655350339/ie213/Capture4_ou6j25.png)
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1655350339/ie213/Capture5_ygryst.png)
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1655350340/ie213/Capture6_gp8ldv.png)
    - Sau khi thanh toán thành công
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1655350341/ie213/Capture7_m8thhe.png)


- Trang thông tin người dùng
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1654943920/ie213/Capture8_y11khn.png)
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1654943920/ie213/Capture9_fdsko1.png)

- ### **Trang Quản Lý**
- Trang thống kê
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1655466124/ie213/Capture4_zk1dpe.png)
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1655466124/ie213/Capture5_tbhb2p.png)
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1655466124/ie213/Capture6_invckk.png)
- Trang quản lý sách
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1654944198/ie213/Capture12_ezvvik.png)
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1654944198/ie213/Capture13_tjjhau.png)
    - Thêm sách
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1654944198/ie213/Capture14_ldhbfd.png)
    - Cập nhật thông tin
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1654944199/ie213/Capture15_cjzfh0.png)

- Quản lý đơn hàng
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1655466124/ie213/Capture1_gblsyf.png)
    - Chi tiết đơn hàng
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1655466124/ie213/Capture2_knqd7r.png)
    - Cập nhật trạng thái đơn hàng
    ![](https://res.cloudinary.com/dbynglvwk/image/upload/v1655466370/ie213/Capture7_k9oes3.png)


## Setup Local Development Enviroment

1. Git clone
```
    https://github.com/ngonhan71/ie213-bookstore-backend
    cd ie213-bookstore-backend
```
2. Install dependencies:
```
    npm install
```
3. Create .env file
```
    PORT = 5000

    SESSION_SECRET=

    PORT=5000
    MONGODB_CONNECT_URI=

    JWT_ACCESS_TOKEN_SECRET=
    JWT_REFRESH_TOKEN_SECRET=

    CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
    CLOUDINARY_API_KEY=your_cloudinary_api_key
    CLOUDINARY_API_SECRET=your_cloudinary_api_secret

    GOOGLE_GMAIL_CLIENT_ID=
    GOOGLE_GMAIL_CLIENT_SECRET=
    GOOGLE_GMAIL_REDIRECT_URI=
    GOOGLE_GMAIL_REFRESH_TOKEN=
```
