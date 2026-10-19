# Học Mã Morse

Ứng dụng web học **mã Morse quốc tế (bộ ký tự tiếng Anh)** từ con số 0: có giáo trình theo bài, bài tập nghe – đọc – gõ, ôn tập ngắt quãng, trò chơi và công cụ giải mã. Toàn bộ nằm trong **một file HTML duy nhất**, chạy **hoàn toàn offline**, không cần cài đặt hay kết nối mạng.

Giao diện tiếng Việt, có chế độ sáng/tối và dùng tốt trên cả máy tính lẫn điện thoại.

---

## Bắt đầu nhanh

1. Tải file [`morse-trainer.html`](morse-trainer.html) về máy.
2. Nhấp đúp để mở bằng trình duyệt (khuyến nghị **Chrome** hoặc **Edge** bản mới).
3. Vào **Bài học → Bài 1** và bắt đầu.

Không cần server, không cần Internet. Có thể chép file sang USB hay điện thoại để học ở bất cứ đâu.

> **Lưu ý khi gõ đáp án:** hãy tắt bộ gõ tiếng Việt (Unikey/EVKey: `Ctrl+Shift` hoặc `Alt+Z`). Bộ gõ Telex có thể biến `AS` thành `Á` khiến đáp án bị chấm sai. App sẽ hiện cảnh báo khi phát hiện.

---

## Tính năng

### Bài học — giáo trình 16 bài


| #      | Nội dung                                                                 |
| ------ | ------------------------------------------------------------------------- |
| 1–4   | Chữ cái theo độ dài mã:`E T` → `I A N M` → `S U R W` → `D K G O` |
| 5      | Ôn tập 1                                                                |
| 6–8   | `H V F L` → `P J B X` → `C Y Z Q`                                       |
| 9      | Ôn tập 2 — toàn bộ 26 chữ cái                                      |
| 10–11 | Chữ số`1–5`, `6–0`                                                    |
| 12–14 | Dấu câu và ký hiệu:`. , ? /` · `= + - : ;` · `( ) ' " @`           |
| 15     | Ngôn ngữ vô tuyến: Q-code, chữ viết tắt (CQ, DE, 73, QTH, RST…)   |
| 16     | Tổng ôn với câu tiếng Anh hoàn chỉnh                               |

Mỗi bài gồm thẻ làm quen ký tự (âm thanh, hình chấm/gạch, nhịp *di-dah*, mẹo nhớ), câu trắc nghiệm nghe/nhìn, câu gõ ký tự và gõ mã, rồi 3 bài đoạn văn ngẫu nhiên: **đọc mã**, **nghe chép**, **gõ mã**. Câu sai được hỏi lại cuối bài; đạt từ 80% để hoàn thành và mở bài tiếp theo.

### Luyện tập — 10 chế độ

- **Nghe & chép / Đọc mã / Gõ mã** — đoạn văn ngẫu nhiên từ nhóm ký tự, từ tiếng Anh, câu, hội thoại vô tuyến hoặc hô hiệu & số; chọn được bộ ký tự và độ dài.
- **Phản xạ** — nhận diện từng ký tự thật nhanh, đo thời gian phản ứng.
- **Telegraph** — tự phát Morse bằng phím, máy giải mã ngay, kèm **phân tích tay gõ** (độ dài chấm/gạch, các khoảng nghỉ so với chuẩn 1 : 3 : 1 : 3 : 7, độ đều tay và lời khuyên).
- **Chép liên tục** — nghe một đoạn dài 1–5 phút không dừng, gõ theo thời gian thực, giống bài thi chép tin.
- **Nghe từ** — các từ thông dụng phát liền ở 15–30 WPM để tập nghe cả từ.
- **Cặp dễ nhầm** — app ghi lại các cặp bạn hay nhầm (vd. `S`/`H`, `U`/`V`) và cho luyện phân biệt riêng.
- **Mô phỏng QSO** — liên lạc 8 lượt với một trạm ảo: bạn phát CQ, báo cáo RST, tên, QTH…; nghe và chép thông tin trạm kia.
- **Giải mã micro** — nghe Morse qua micro, tự dò tần số và tốc độ, dịch ra chữ. Có tín hiệu mẫu để chạy thử.

### Trò chơi

- **Rhythm game** — giữ phím đúng nhịp theo các vạch chạy, chấm Perfect/Great/Good/Miss, có combo, hạng S–D, kỷ lục theo tốc độ và chế độ xem lại.
- **Mưa chữ** — gõ đúng ký tự trước khi mã rơi chạm đáy; chế độ *Nhìn mã* hoặc *Nghe âm*.
- **Thử thách 60 giây** — nghe và gõ càng nhiều ký tự càng tốt.

### Ôn tập & tiến bộ

- **Lặp lại ngắt quãng (Leitner)** — ký tự hay sai được hỏi thường xuyên hơn; ký tự đã thuộc giãn lịch ôn 1 → 2 → 4 → 7 → 15 → 30 ngày.
- **Biểu đồ tiến bộ** — số câu mỗi ngày, độ chính xác, tốc độ nghe đạt được, lịch học 18 tuần; danh sách ký tự yếu và cặp hay nhầm.
- **Bản đồ ký tự** — độ chính xác và cấp ghi nhớ của từng ký tự.

### Âm thanh & cách trả lời

- Chỉnh **tốc độ ký tự (WPM)**, **Farnsworth** (giãn khoảng nghỉ), tần số, âm lượng, dạng sóng.
- **Tự tăng tốc** khi nghe tốt (3 bài liên tiếp ≥ 90%), tự giảm khi sai nhiều.
- **Mô phỏng sóng vô tuyến** 4 mức (Sạch / Nhẹ / Vừa / Khó): nhiễu nền, tín hiệu lúc mạnh lúc yếu, trạm khác chen vào, trôi tần số.
- **Chế độ im lặng** — phát tín hiệu bằng rung (điện thoại Android) kèm đèn tín hiệu nháy.
- **Trả lời bằng ấn giữ tín hiệu** — ở mọi câu cần gõ, có thể chọn tự phát Morse (giữ `Space` hoặc chạm giữ nút lớn) thay vì gõ chữ.

### Bảng mã

Bảng tra chữ cái, chữ số, dấu câu, prosign (có âm thanh), bộ chuyển đổi chữ ↔ Morse hai chiều, cây nhị phân Morse và giải thích quy tắc thời gian.

---

## Phím tắt


| Phím           | Chức năng                                                        |
| --------------- | ------------------------------------------------------------------ |
| `Enter`         | Kiểm tra / tiếp tục                                             |
| `1` – `4`      | Chọn đáp án trắc nghiệm                                      |
| `Space`         | Nghe lại (thẻ học, câu trắc nghiệm)                          |
| `Ctrl + Space`  | Nghe lại khi đang gõ đáp án                                  |
| `Shift + Enter` | Xuống dòng trong ô đoạn văn                                  |
| `Space` (giữ)  | Phát tín hiệu: trả lời bằng ấn giữ, Telegraph, Rhythm game |
| `Ctrl + Enter`  | Chấm điểm bài Chép liên tục                                 |
| `Esc`           | Dừng bài Phản xạ, Nghe từ, Cặp dễ nhầm, trò chơi         |

---

## Dữ liệu & quyền riêng tư

- Tiến độ, thống kê và cài đặt được lưu **ngay trong trình duyệt** (`localStorage`). Không có tài khoản, không gửi dữ liệu đi đâu.
- Khi đổi máy hoặc trình duyệt: vào **Cài đặt → Xuất tiến độ** để lưu file `.json`, rồi **Nhập tiến độ** ở nơi mới.
- Xoá dữ liệu trình duyệt sẽ xoá luôn tiến độ — nên xuất file sao lưu định kỳ.
- Âm thanh từ micro (chế độ *Giải mã micro*) chỉ được xử lý trên máy của bạn.

---

## Tương thích


| Tính năng                   | Hỗ trợ                                                                                                                     |
| ----------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Học, luyện tập, trò chơi | Chrome, Edge, Firefox, Safari bản mới (máy tính & điện thoại)                                                         |
| Rung (chế độ im lặng)     | Chỉ điện thoại**Android** (Chrome/Edge). iPhone, iPad và máy tính không có rung — đèn tín hiệu nháy thay thế |
| Giải mã micro               | Cần cấp quyền micro; tốt nhất trên Chrome/Edge                                                                         |
| Offline                       | Mọi tính năng, không cần Internet                                                                                       |

---

## Về kỹ thuật

- **Một file HTML** (~230 KB): HTML + CSS + JavaScript thuần, không framework, không thư viện ngoài, không tải tài nguyên từ mạng.
- Âm thanh tạo bằng **Web Audio API** theo chuẩn thời gian PARIS (chấm 1 · gạch 3 · nghỉ trong ký tự 1 · giữa ký tự 3 · giữa từ 7 đơn vị) và công thức Farnsworth.
- Giải mã micro dùng thuật toán **Goertzel** đo cường độ tại tần số âm, ngưỡng thích nghi và phân cụm độ dài tín hiệu để tự nhận tốc độ.
- Chấm điểm đoạn văn bằng căn chỉnh **Levenshtein**, hiển thị chi tiết ký tự đúng / sai / thiếu / thừa.
- Biểu đồ vẽ bằng SVG thuần, tự theo giao diện sáng/tối.

---

## Mẹo học hiệu quả

- **Học bằng tai**: nhớ nhịp *di-dah* của cả ký tự như một âm thanh, đừng đếm từng chấm gạch.
- Giữ **tốc độ ký tự 15–20 WPM** ngay từ đầu, dùng **Farnsworth** thấp để có thời gian suy nghĩ; tăng dần khi đã quen (hoặc bật *Tự tăng tốc*).
- **15–20 phút mỗi ngày** hiệu quả hơn học dồn; vào **Ôn tập** mỗi ngày để giữ trí nhớ.
- Khi đã nghe tốt trong điều kiện sạch, bật **mô phỏng sóng** và thử **Chép liên tục**, **Mô phỏng QSO** để làm quen điều kiện thực tế.
