# Cẩm nang viết học liệu Kinh tế lượng dành cho bé Mei

> Mục tiêu tối thượng: biến một môn **bị mang tiếng đáng sợ** thành môn **hấp dẫn, đi từ trực giác, không dọa người đọc**. Mọi file `.qmd` trong repo này phải tuân theo cẩm nang này.

## Persona giọng văn: NGƯỜI BỐ ẤM ÁP ĐANG DẠY CON
- Người kể là **"bố"**, người đọc là **"con" / "Mei"**. Không dùng "bạn", không dùng "sinh viên".
- Giọng **trìu mến, kiên nhẫn, động viên**: "đừng lo con", "từ từ thôi", "bố tin con", "bố dặn con".
- Bố **thừa nhận môn này từng làm chính bố sợ**, rồi trấn an con.
- Tránh sến quá đà hoặc lên gân; ấm áp nhưng vẫn **dạy kiến thức thật, chính xác**.
- Câu chốt mỗi mục mở bằng "Bố chốt cho con:" hoặc "Bố dặn con:".
- Header callout viết theo lời bố: "🎯 Bố mong sau buổi này con sẽ…", "💡 Bố nói nhỏ con nghe", "⚠️ Cái bẫy bố dặn con tránh", "🔑 Ba điều bố muốn con mang về", "🔍 Khi nào con muốn đào sâu".

## Nỗi sợ của người học (phải gỡ)
1. "Toàn ký hiệu Hy Lạp, mình dốt toán." → Ký hiệu chỉ là **biệt danh viết tắt**, luôn dịch sang tiếng người ngay khi xuất hiện.
2. "Phải học thuộc công thức." → Không. Máy tính tính; người học **suy nghĩ và diễn giải**.
3. "Trừu tượng, chẳng liên quan đời mình." → Mỗi khái niệm gắn một **câu hỏi đời thực** người đọc thật sự tò mò.
4. "Một buổi nhồi 10 thứ." → **Một ý lớn mỗi buổi.**

## Nguyên tắc cốt lõi (the ladder)
Trình bày MỌI khái niệm theo thang 4 bậc, **không bao giờ bắt đầu bằng công thức**:

```
① Câu hỏi / câu chuyện  →  ② Hình ảnh, trực giác  →  ③ Ví dụ bằng số cụ thể  →  ④ Công thức (nếu cần)
```

- **Tại sao** trước **làm thế nào**. Động lực trước cơ chế.
- **Toán là tùy chọn**: chứng minh/đại số đặt trong callout có thể gập (`.callout-note collapse="true"`) hoặc mục "Dành cho ai muốn đào sâu". Người sợ toán vẫn theo trọn mạch chính.
- **Thấy bằng số**: mỗi khái niệm trỏ tới một lab (Stata/R/Python) để người đọc tự tay chạy.
- **Ví dụ kép cho mỗi khái niệm**: một ví dụ "người lớn" (lương–học vấn, giá nhà, điểm thi…) đi kèm **một ví dụ gần với con Mei** (luyện đọc, nhảy dây, tưới cây, luyện đàn…), khép lại bằng câu kiểu *"cùng một trò chơi, chỉ thay tên hai trục thôi con"*. Mục đích: để con luôn thấy chính mình trong bài.

## Giọng văn
- Giọng đồng hành, ấm áp — không phán xét, không hàn lâm khô khan (xưng **"bố" / "con"**, xem Persona ở trên).
- **Câu ngắn, chủ động.** Mỗi đoạn một ý.
- Ẩn dụ đời thường (đám mây điểm, đường xu hướng, cái cân...).
- **Gọi tên nỗi sợ rồi hạ nó xuống:** "Chỗ này nhìn đáng sợ, nhưng thực ra chỉ là…".
- Ví dụ **dữ liệu Việt Nam**: lương–học vấn, giá nhà, điểm thi, doanh thu quán cà phê…

## Bảng callout dùng thống nhất (Quarto)
| Callout | Dùng cho |
|---|---|
| `::: {.callout-tip}` 💡 **Trực giác** | giải thích bằng hình ảnh/ẩn dụ |
| `::: {.callout-note}` 🎯 **Mục tiêu / Chốt lại** | mục tiêu buổi, tóm ý |
| `::: {.callout-warning}` ⚠️ **Bẫy thường gặp** | hiểu lầm phổ biến |
| `::: {.callout-important}` 🧮 **Ví dụ bằng số** | con số cụ thể |
| `::: {.callout-note collapse="true"}` 🔍 **Đào sâu** | toán/chứng minh tùy chọn |

## Khung mỗi buổi giảng
1. **Hook** — 1 câu hỏi đời thực mở đầu.
2. 🎯 **Mục tiêu** (callout) — 2–3 gạch đầu dòng, ngôn ngữ kết quả.
3. **Thân bài** theo thang 4 bậc, mỗi mục đóng bằng 1 câu "chốt lại".
4. **Thấy bằng số** — link tới lab tương ứng.
5. 🔑 **Chốt lại buổi** — 3 ý người đọc mang về.
6. *(Tùy chọn)* 🔍 Đào sâu — phần toán cho người muốn.

## Checklist trước khi coi một file là "xong"
- [ ] Mở đầu bằng **câu hỏi**, không phải định nghĩa.
- [ ] Mọi ký hiệu được **dịch sang tiếng người** ngay lần đầu.
- [ ] Có ít nhất 1 **ví dụ bằng số** và 1 **hình ảnh/ẩn dụ**.
- [ ] Phần toán nặng nằm trong callout gập được.
- [ ] Có **chốt lại** cuối mỗi mục lớn và cuối buổi.
- [ ] Một người **chưa từng học** đọc xong vẫn không thấy sợ.
