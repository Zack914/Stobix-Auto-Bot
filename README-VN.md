Dưới đây là bản dịch tiếng Việt cho tài liệu **Stobix Auto Bot**:

---

# 🤖 Stobix Auto Bot

**Stobix Auto Bot** là một công cụ tự động hóa được thiết kế để tương tác với nền tảng Stobix nhằm mục đích *farming airdrop*. Bot này sẽ tự động thực hiện các tác vụ sau:

- Tự động nhận các nhiệm vụ có sẵn  
- Bắt đầu và theo dõi quá trình khai thác (mining)  
- Hỗ trợ nhiều ví với khả năng dùng proxy  
- Theo dõi trạng thái khai thác theo chu kỳ

---

## 📝 Đăng ký

- Trang web: https://stobix.com/

---

## 🌟 Tính năng

- ✅ Hỗ trợ nhiều ví  
- ✅ Hỗ trợ proxy để tránh giới hạn IP  
- ✅ Tự động nhận nhiệm vụ  
- ✅ Tự động khai thác và kiểm tra trạng thái định kỳ  
- ✅ Giao diện console có màu sắc trực quan  
- ✅ Cơ chế xử lý lỗi và thử lại thông minh  

---

## 🛠️ Yêu cầu

- **Node.js** (phiên bản 16 trở lên)  
- **npm** hoặc **yarn**

---

## ⚙️ Cài đặt

1. Clone repo:

```bash
git clone https://github.com/Zack914/Stobix-Auto-Bot.git
cd Stobix-Auto-Bot
```

2. Cài đặt các thư viện cần thiết:

```bash
npm install
```

3. Tạo file `.env` và thêm private key của bạn:

```bash
cp .env.example .env
```

4. Chỉnh sửa file `.env` và thêm các private key:

```
PRIVATE_KEY_1=private_key_thu_nhat_cua_ban
PRIVATE_KEY_2=private_key_thu_hai_cua_ban
```

5. (Tùy chọn) Cấu hình proxy bằng cách tạo file `proxies.txt` (mỗi proxy trên một dòng):

```
http://username:password@proxy1.example.com:8080
username:password@proxy2.example.com:8080
```

---

## 🚀 Cách sử dụng

Khởi chạy bot bằng lệnh:

```bash
node index.js
```

Bot sẽ:
1. Xử lý lần lượt từng ví  
2. Tự động nhận các nhiệm vụ có sẵn  
3. Bắt đầu khai thác nếu chưa khai thác  
4. Theo dõi trạng thái khai thác mỗi giờ và khởi động lại nếu cần

---

## 🧾 Các nhiệm vụ tự động hóa

Bot sẽ tự động nhận điểm từ các nhiệm vụ sau:
- Theo dõi trên X (Twitter)  
- Tham gia máy chủ Discord  
- Tham gia kênh Telegram  
- Tham gia nhóm chat Telegram  
- Bắt đầu bot Telegram  
- Đánh giá trên Trustpilot  

---

## 🎨 Giao diện Console

Bot hiển thị trạng thái bằng màu sắc rõ ràng:
- ✅ Màu xanh lá: Thông báo thành công  
- ⚠️ Màu vàng: Cảnh báo  
- ❌ Màu đỏ: Lỗi  
- ⟳ Màu xanh dương nhạt: Đang xử lý / Thông tin  
- ➤ Màu trắng: Các bước đang thực hiện

---

## ⚠️ Cảnh báo

Bot này chỉ dành cho mục đích học tập. Bạn tự chịu trách nhiệm khi sử dụng. Tác giả không chịu trách nhiệm với bất kỳ rủi ro nào.

---

## 📜 Giấy phép

Giấy phép sử dụng theo **MIT License**
