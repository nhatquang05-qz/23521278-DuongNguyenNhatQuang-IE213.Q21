# Thông tin sinh viên

- **Họ và tên:** Dương Nguyễn Nhật Quang  
- **MSSV:** 23521278  
- **Lớp:** IE213.Q21  

---

# Danh sách các Lab

## Lab01
**Nội dung:**  
Tiến hành cài đặt MongoDB và thực hiện một số thao tác CRUD cơ bản.

**Cách chạy:**  
- Dùng Mongosh của MongoDB Compass. 
- Copy và paste script trong README.md ở thư mục Lab01 để chạy.

**Trạng thái:** Đã hoàn thành tất cả nội dung.

![Lab01](./images/lab01.png)

---

## Lab02
**Nội dung:** Thiết lập backend với Node.js và ExpressJS.

**Cách chạy:**   
1. Mở terminal, điều hướng vào thư mục backend: `cd Lab02/movie-reviews/backend`.  
2. Chạy lệnh `npm install` để cài đặt các dependency cần thiết (đã được định nghĩa trong `package.json`).  
3. Đảm bảo file `.env` đã được đặt ở thư mục backend và cấu hình chuỗi kết nối `MOVIEREVIEWS_DB_URI` và `PORT=3000`.  
4. Chạy lệnh `npm start` (hoặc `node index.js`) để khởi động máy chủ web. Terminal sẽ báo `Server is running on port: 3000`.  
5. Sử dụng Postman, tạo một HTTP GET Request tới đường dẫn `http://localhost:3000/api/v1/movies` để kiểm tra dữ liệu JSON trả về.  

**Trạng thái:** Đã hoàn thành tất cả nội dung.

![Lab02](./images/lab02.png)