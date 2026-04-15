# Arduino LM35 Temperature Monitoring System

## Mô tả dự án
Dự án sử dụng cảm biến nhiệt độ LM35 kết hợp với Arduino để đọc dữ liệu từ 3 kênh analog (A0, A1, A2) và gửi dữ liệu qua Serial dưới dạng JSON. 
Hệ thống mô phỏng việc thu thập dữ liệu từ nhiều cảm biến và có thể mở rộng cho các ứng dụng IoT.

## Tính năng
- Đọc dữ liệu từ 3 cảm biến LM35
- Chuyển đổi tín hiệu analog sang giá trị nhiệt độ (°C)
- Gửi dữ liệu qua Serial dưới dạng JSON
- Cấu trúc chương trình đơn giản, dễ mở rộng

## Phần cứng cần thiết

| Thiết bị       | Số lượng 	| Mô tả                    	|
|----------------|-------------	|------------------------------	|
| Arduino UNO    | 1        	| Vi điều khiển chính       	|
| LM35           | 3        	| Cảm biến nhiệt độ         	|
| Breadboard     | 1        	| Mạch thử                  	|
| Dây nối        | Nhiều    	| Kết nối mạch             	|
| Cáp USB        | 1        	| Kết nối Arduino với máy tính 	|

## Cách sử dụng

1. Kết nối phần cứng theo sơ đồ mạch (A0, A1, A2)
2. Mở Arduino IDE
3. Nạp chương trình vào Arduino UNO
4. Mở Serial Monitor với baud rate 9600
5. Quan sát dữ liệu JSON được gửi lên

## Cấu trúc thư mục

Arduino_LM35_TempMonitor/
├── firmware/
│   └── LM35_TempReader/
│       └── LM35_TempReader.ino
├── pc_app/
├── docs/
├── libs/
├── simulation/
└── README.md

## Thành viên nhóm

1. Nguyễn Văn A: xử lý cảm biến và đọc dữ liệu
2. Trần Thị B: xử lý Git merge conflict và tối ưu code
3. Lê Văn C: viết tài liệu và README

## Tac gia
[Pham Van Huu Dang ](https://PVHuuDang.github.io) - Sinh vien PTIT
