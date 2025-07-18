# HƯỚNG DẪN SỬ DỤNG BÀN PHÍM WIRELESS (ZMK)

## 1. THÔNG TIN CƠ BẢN
- **Công tắc nguồn**: Nằm ở đầu dưới jack cắm Type-C của MCU
- **Kiểu kết nối**: Bluetooth hoặc có dây
- **Số layer**: 3 layer chính có thể keymap thêm (mặc định, lower, raise)
- **Số nút**: 
  - 42 (có thể giảm xuống 36 phím) với Corne v4
  - 58 phím với Sofle RGB v2.1 PandaKB
- **OLED màn hình**: Hiển thị pin, chế độ kết nối, layer hiện tại, trạng thái Bluetooth
- **LED**: Không có
- **Pin**: 550mAh x 2 = 1100mAh
- **Hotswap**: Có thể thay thế switch thoải mái

## 2. CÁC LAYER CHÍNH
- **Layer 0 (Mặc định)**: Layer cơ bản
- **Layer 1 (Lower)**: 
  - Kích hoạt bằng phím LWR (nút ở mạch trái, chính giữa hàng dưới cùng)
- **Layer 2 (Raise)**: 
  - Kích hoạt bằng phím RSE (nút ở mạch phải, chính giữa hàng dưới cùng)

## 3. HƯỚNG DẪN KẾT NỐI
### Kết nối không dây:
1. **Bật nguồn**: Gạt công tắc ở đầu dưới jack Type-C của mạch
2. **Tự động kết nối**:
   - Mạch phải tự động dò tìm và kết nối không dây với mạch trái
   - Đèn LED nhấp nháy trong quá trình kết nối và sáng ổn định khi thành công
3. **Kết nối với thiết bị**:
   - Bật Bluetooth trên thiết bị và dò tìm tên bàn phím (Corne/Sofle)
   - Nhấn Connect, nếu thành công kiểm tra màn OLED hiển thị dấu ✓

### Kết nối có dây:
1. Cắm cáp Type-C vào mạch trái (không cần cáp TRRS 3.5mm giữa 2 mạch)
2. Hệ thống tự động chuyển sang chế độ có dây
3. Mạch phải nhận nguồn và tín hiệu từ mạch trái qua kết nối không dây

## 4. HƯỚNG DẪN LẮP ĐẶT & SỬ DỤNG
- **Lắp switch/keycap (đối với kit DIY)**:
  1. Tháo Plate ra khỏi Case
  2. Gắn switch lên Plate, đặt vào PCB, nhấn xuống đồng loạt
  3. Lắp lại vào Case và gắn keycap
- **Truy cập layer Adjust**: Giữ phím LWR hoặc RSE đồng thời nhấn các nút khác
- **Keymap**: Chỉnh sửa nếu vị trí nút không phù hợp

## 5. XỬ LÝ SỰ CỐ
- **Không kết nối được**: Thử BT CLR để xóa thiết bị trên Bluetooth và ghép nối lại
- **Kết nối không ổn định**:
  - Kiểm tra lại keymap hoặc nạp firmware mới
  - Đảm bảo thiết bị hỗ trợ Bluetooth 5.0+ (không dùng USB Bluetooth adapter)
- **Pin hao nhanh**:
  - Trước khi keymap: Vệ sinh mạch, kiểm tra ngoại quan. Nếu vẫn lỗi, liên hệ shop
  - Sau khi keymap: Có thể do thao tác sai → keymap lại
- **Lỗi nghiêm trọng**: Liên hệ đổi mạch hoặc bồi thường (nếu có)

## 6. KEYMAP CÁ NHÂN
Tham khảo hướng dẫn keymap bằng cách:
- Quét QR code đi kèm
- Truy cập web: [github.com/hieupham0012](https://github.com/hieupham0012)

**Lưu ý**:
- Sofle v2.1 RGB PandaKB và Corne v4 Wireless layout 42 có thể keymap khác theo nhu cầu

  
