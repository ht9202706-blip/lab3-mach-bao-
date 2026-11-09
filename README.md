# lab3-mach-bao-
Báo cáo Lab 3 - ESP32 + FreeRTOS + MQTT
https://wokwi.com/projects/477959412037374977
# BÁO CÁO LAB 3 - MẠCH BÁO CHÁY GIA ĐÌNH

## 1. Thông tin đề tài
Thiết kế mạch báo cháy gia đình sử dụng ESP32, FreeRTOS, cảm biến MQ2, DHT22 và giao thức MQTT.

## 2. Báo cáo
[Download báo cáo Lab 3](./Bao_cao_Lab_3_Mach_bao_chay_ESP32_FreeRTOS_MQTT.docx)

## 3. Mô phỏng Wokwi
[Dán link Wokwi tại đây]([DAN_LINK_WOKWI](https://wokwi.com/projects/477959412037374977))

## 4. Giao diện Website
[Dán link Website tại đây](DAN_LINK_WEBSITE)

## 5. Mã nguồn
- sketch.ino: Chương trình ESP32 và FreeRTOS.
- diagram.json: Sơ đồ kết nối mạch.
- index.html: Giao diện Web giám sát và điều khiển.

## 6. Chức năng hệ thống
- Đọc nồng độ khí gas từ MQ2.
- Đọc nhiệt độ từ DHT22.
- Sử dụng FreeRTOS với 3 Task.
- Truyền dữ liệu qua MQTT Broker.
- Hiển thị dữ liệu theo thời gian thực.
- Điều khiển quạt và máy bơm ở chế độ MANUAL.
- Cảnh báo tự động khi vượt ngưỡng.
