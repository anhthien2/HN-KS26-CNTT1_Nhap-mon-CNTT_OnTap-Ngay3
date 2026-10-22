# Ôn tập ngày 3
- Tên : Trần Đức Thiện
- Lớp: CNTT1
- Link repository
- Hệ Điều Hành: Windows

## Bài 1.


- [x] Heading 1: `# Trung Tam...`
- [x] 2 heading cấp 2: `## Gioi thieu`, `## Cau truc...`
- [x] In đậm + in nghiêng: `**website...**` và `*giao dien...*`
- [x] Bảng 3 dòng: data, docs, logs 
- [x] Danh sách đánh số 3 bước: 1,2,3 quy trình đăng ký
- [x] Code block: `dir -Recurse`
- [x] Task list: có `[x]` đã xong và `[ ]` chưa xong
- [x] Blockquote: `> Luu y`
## Bài 2.


**Vì sao vùng tra cứu cần dấu**  **

Dấu `$` để tạo **tham chiếu tuyệt đối**, khóa cứng vùng bảng `A2:C8` lại. Để khi kéo công thức từ dòng 2 xuống dòng 16 thì nó vẫn dò đúng trong bảng 7 khóa học ở sheet KhoaHoc.

**Nếu bỏ dấu**  **$ thì sao?**

Nếu chỉ ghi `KhoaHoc!A2:C8` (tham chiếu tương đối), khi kéo xuống:

-   Dòng 3 sẽ tự thành `A3:C9`
-   Dòng 4 thành `A4:C10`
-   Dòng 16 thành `A16:C22`

Vùng dò bị trôi xuống, lệch khỏi bảng gốc, không còn chứa đủ dữ liệu nữa. Kết quả là VLOOKUP sẽ báo lỗi `#N/A` hoặc trả về sai tên khóa / sai học phí
