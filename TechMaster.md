# Thiết kế ứng dụng quản lý thiết bị của TechMaster

## Đối tượng chủ thể - USERS
1. CEO
2. Giảng Viên
3. Học Viên
4. Phụ Huynh


## Đối tượng không phải người - OBJECTS
1. Thiết Bị
2. Kho
3. Phòng Học
4. Phòng Điều Hành
5. Phòng Tiếp Khách

## Hành động - ACTIONS / VERBS
1. Học viên thực tập cả ngày
2. Học viên thực tập nửa ngày (có thể phân ra buổi sáng và buổi chiều)
3. Học viên báo cáo thiết bị khi gặp sự cố
4. Giảng viên tổng hợp thông tin từ học viên
5. Giảng viên báo cáo lại với CEO khi có vấn đề với thiết bị


> Học viên tự quản lý thiết bị khi đã được cấp riêng để sử dụng

## Sự kiện - EVENTS kết quả sau của hành động
1. Sửa chữa thiết bị nếu có thể sửa lỗi
2. Nhập thiết bị mới
3. Cấp phát cho các phòng
4. Mua thêm thiết bị khi có thêm học viên
5. Cài đặt thiết bị

## Ngoại lệ - EXCEPTIONS
1. Cháy nổ
2. Mất điện
3. Mất đồ
4. Học viên chậm trễ đóng học phí
5. Học viên làm hỏng thiết bị
