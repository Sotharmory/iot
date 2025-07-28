Dự án Cửa Tự Động Thông Minh – IoT Embedded System

📖 Giới thiệu

Dự án Cửa Tự Động Thông Minh sử dụng công nghệ IoT kết hợp hệ nhúng để tự động đóng/mở cửa dựa trên cảm biến phát hiện người. Hệ thống có thể điều khiển từ xa qua Internet và giám sát trạng thái cửa theo thời gian thực.

⚙️ Phần cứng sử dụng

✅ Vi điều khiển: ESP32 / Arduino UNO / STM32 (tuỳ chọn)
✅ Cảm biến:
PIR Sensor (Phát hiện chuyển động)
Cảm biến từ (phát hiện trạng thái đóng/mở cửa)
✅ Động cơ: Servo / Động cơ DC + Driver L298N
✅ Kết nối: WiFi (ESP32) hoặc Bluetooth (HC-05 nếu không dùng WiFi)
✅ Nguồn điện: 5V–12V DC (tuỳ loại động cơ)
🧠 Phần mềm sử dụng

Ngôn ngữ: C/C++ (Arduino IDE hoặc PlatformIO)
Giao thức truyền: MQTT hoặc HTTP (REST API)
Nền tảng IoT (tùy chọn): Blynk / Firebase / Node-RED / ThingsBoard
Tính năng điều khiển từ xa: App điện thoại hoặc giao diện Web
🛠️ Các chức năng chính

Tính năng	Mô tả
🚶‍♂️ Phát hiện người	Dùng cảm biến PIR để tự động mở cửa khi có người tiếp cận
🚪 Điều khiển cửa	Động cơ mở/đóng cửa theo tín hiệu từ cảm biến hoặc lệnh từ xa
📱 Điều khiển từ xa	Gửi lệnh mở/đóng cửa từ ứng dụng điện thoại/web qua WiFi
📊 Giám sát trạng thái	Hiển thị trạng thái cửa (đóng/mở) theo thời gian thực trên app/web
🔐 Bảo mật cơ bản	Mã hóa đơn giản hoặc giới hạn IP điều khiển (nếu cần)
📲 Hướng dẫn cài đặt

Kết nối phần cứng theo sơ đồ mạch (đính kèm hình ảnh sơ đồ nếu có).
Nạp chương trình vào vi điều khiển qua Arduino IDE.
Cài đặt app hoặc giao diện web điều khiển.
Cấu hình WiFi / MQTT Broker trong file config.h.
Khởi động hệ thống và kiểm tra hoạt động.
