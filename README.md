# EmailWeb

EmailWeb là một ứng dụng web được xây dựng bằng Java, sử dụng Spring Boot để gửi và nhận email thông qua giao diện người dùng đơn giản.

## 🚀 Giới thiệu

Ứng dụng cho phép người dùng:

- Gửi email với nội dung và đính kèm.
- Quản lý danh sách liên lạc.
- Tích hợp với hệ thống email phổ biến như Gmail, Outlook.

## 🛠️ Công nghệ sử dụng

- **Backend**: Java, Spring Boot
- **Frontend**: HTML, CSS
- **Container**: Docker (có sẵn Dockerfile)
- **Quản lý phụ thuộc**: Maven (pom.xml)

## 📦 Cài đặt và chạy ứng dụng

### 1. Cài đặt yêu cầu

- Java 11 trở lên
- Maven
- Docker (nếu muốn chạy trong container)

### 2. Cấu hình ứng dụng

- Mở `src/main/resources/application.properties` và cấu hình các thông số sau:

  ```properties
  spring.mail.host=smtp.gmail.com
  spring.mail.port=587
  spring.mail.username=your-email@gmail.com
  spring.mail.password=your-email-password


3. Chạy ứng dụng

Sử dụng Maven:

mvn spring-boot:run


Sử dụng Docker:

docker build -t emailweb .
docker run -p 8080:8080 emailweb

4. Truy cập ứng dụng

Mở trình duyệt và truy cập: http://localhost:8080

🧪 Kiểm thử

Ứng dụng đã được kiểm thử với các trường hợp:

Gửi email đơn giản.

Gửi email với tệp đính kèm.

Quản lý danh bạ.

📄 Giấy phép

Đây là dự án mã nguồn mở, được cấp phép theo MIT License
.

📞 Liên hệ

GitHub: https://github.com/Baopham1607

Email: baopham1607@example.com
