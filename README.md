# Kinh tế lượng dành cho bé Mei

Học liệu **Kinh tế lượng** kể bằng giọng người bố ấm áp đang dạy con — viết cho bé Mei. Đi từ trực giác trước, công thức sau, không làm người đọc sợ.

Trang web được xây bằng [Quarto](https://quarto.org/), cấu trúc theo khuôn của môn [Nguyên lý Quản lý Kinh tế](https://github.com/dongkien/nlqlkt). Xem [WRITING-GUIDE.md](WRITING-GUIDE.md) để biết triết lý & giọng viết.

## Cấu trúc

```
.
├── _quarto.yml          # Cấu hình website (navbar, sidebar, theme)
├── index.qmd            # Trang chủ
├── syllabus.qmd         # Đề cương
├── schedule.qmd         # Lịch học
├── lectures/            # Bài giảng (buoi-01 … buoi-15)
├── stata-lab/           # Lab Stata (lab-00 … lab-15)
├── r-lab/               # Lab R
├── python-lab/          # Lab Python
├── problem-sets/        # Tiểu luận / bài tập
├── exams/               # Đánh giá
├── data/                # Bộ dữ liệu
└── styles/              # Theme tuỳ biến (custom.scss)
```

## Phát triển cục bộ

```bash
quarto preview      # xem trực tiếp khi soạn
quarto render       # build ra thư mục _site/
```

## Xuất bản

```bash
quarto publish gh-pages
```

## Giấy phép

Nội dung: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.vi).
