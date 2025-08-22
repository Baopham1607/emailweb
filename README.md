# EmailWeb

EmailWeb là ứng dụng web Java chạy trên Tomcat, sử dụng Maven để build và triển khai trên Render.

## 🚀 Giới thiệu

Ứng dụng cho phép người dùng:

- Gửi email với nội dung và tệp đính kèm.
- Quản lý danh sách liên lạc.
- Chạy trực tiếp trên Tomcat hoặc Render.

## 🛠️ Công nghệ

- **Java**: JDK 17  
- **Build**: Maven 3.9.11  
- **Server**: Tomcat 11  
- **Triển khai**: Render  

## 📦 Quickstart

### 1. Build ứng dụng

Trên máy local:

bash
mvn clean package
Lệnh này sẽ tạo ra tệp target/emailweb.war.

2. Push lên GitHub
git add .
git commit -m "Build package"
git push origin main

3. Triển khai trên Render

Đăng nhập Render
 → chọn New Web Service.

Kết nối repository emailweb.

Chọn Language: Docker.

Chọn Region: Singapore.

Trong Environment Variables, thêm:

PORT=8080


Build Command:

mvn clean package


Start Command: triển khai WAR trên Tomcat hoặc Docker container.

Render sẽ tự động build và deploy ứng dụng. Truy cập qua URL do Render cung cấp.

4. Truy cập ứng dụng

Render: URL hiển thị trên dashboard Render

🧪 Kiểm thử

Ứng dụng đã được kiểm thử với các trường hợp:

Gửi email đơn giản.

Gửi email với tệp đính kèm.

Quản lý danh bạ.

📞 Liên hệ

GitHub: https://github.com/Baopham1607

Email: baopham1607@example.com
