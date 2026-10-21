# (Bài tập tổng hợp) Dựng README.md cho Dự Án CLB SmartCampus


# PHẦN 1 & PHẦN 2: NỘI DUNG FILE README.md DỰ ÁN SMARTCAMPUS

# 📱 SmartCampus

![Logo SmartCampus](https://clblaptrinh.ptit.edu.vn/images/logo.png)

**SmartCampus** là ứng dụng di động hỗ trợ sinh viên PTIT tra cứu lịch học, phòng học trống và cập nhật *thông báo mới nhất* từ nhà trường.

Dự án được xây dựng và duy trì bởi [CLB Lập trình PTIT](https://clblaptrinh.ptit.edu.vn).

### Các tính năng đã hoàn thành:
- Tra cứu lịch học theo mã sinh viên
  - Xem chi tiết phòng học, ca học và tên giảng viên
- Xem danh sách phòng trống theo từng tòa nhà

> ⚠️ **Cảnh báo:** Dự án hiện đang trong giai đoạn thử nghiệm nội bộ, chưa áp dụng cho các hoạt động chính thức của trường.

---

### :rocket: Hướng dẫn cài đặt

Mở Terminal và gõ tuần tự 3 dòng lệnh sau:

```bash
git clone [https://github.com/clb-lap-trinh/smartcampus.git](https://github.com/clb-lap-trinh/smartcampus.git)
npm install
npm start
```
# PHẦN 3: HỎI AI ĐÚNG CÁCH VÀ LƯU TÀI LIỆU
  1. Viết Prompt chuẩn Công thức 3 Phần
  Plaintext
  ## Tôi là ai / Bối cảnh
  Tôi là sinh viên năm nhất ngành CNTT, mới tham gia nhóm làm app SmartCampus của CLB Lập trình PTIT.
  
  ## Chủ đề / Nội dung cần xử lý
  Tôi chưa hiểu rõ thuật ngữ kỹ thuật "API" là gì và cơ chế hoạt động của nó trong ứng dụng di động.
  
  ## Yêu cầu
  - Giải thích khái niệm API bằng 1 ví dụ đời thường thật dễ hiểu (như người phục vụ quán ăn).
  - Nêu rõ vai trò của API khi app SmartCampus kết hợp với thư viện Axios.
  - Trình bày dạng danh sách gạch đầu dòng ngắn gọn, súc tích.
  
  ## Không cần
  - Không giải thích thuật ngữ chuyên sâu phức tạp, không viết code chi tiết.


# PHẦN 4: BẪY CÚ PHÁP MARKDOWN
  1. Chỉ ra 2 lỗi cú pháp trong đoạn mã mẫu
  Lỗi 1 (Bảng): Bảng bị thiếu dòng kẻ phân cách tiêu đề (| :--- | :--- |), khiến trình phân tích Markdown không nhận diện được cấu trúc bảng mà chỉ hiển thị như văn bản thông thường.
  
  Lỗi 2 (Task List): Viết dính liền dấu gạch ngang với dấu ngoặc vuông (-[x] và -[ ]), trong khi quy tắc bắt buộc phải có một khoảng trắng (space) sau dấu gạch ngang (- [x] và - [ ]).
  
  2. Viết lại đoạn mã đã sửa đúng chuẩn
 ``` Markdown
  | Tính năng | Trạng thái |
  | :--- | :--- |
  | Tra cứu lịch học | Xong |
  | Push notification | Đang làm |
  
  - [x] Tra cứu lịch học
  - [ ] Push notification
```
