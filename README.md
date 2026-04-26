# portfolio
# 🌐 Portfolio cá nhân — Vũ Huy Minh

> Trang portfolio cá nhân được triển khai trên **GitHub Pages**  
> 🔗 **Live Website:** [https://vuhuyminh5-arch.github.io/portfolio](https://vuhuyminh5-arch.github.io/portfolio)

---

## 📸 Hình ảnh mô tả

> *(Chụp màn hình website sau khi deploy và thêm vào thư mục `screenshots/`)*

| Hero | Dự án | Chứng chỉ |
|------|-------|-----------|
| ![Hero](screenshots/hero.png) | ![Projects](screenshots/projects.png) | ![Certificates](screenshots/certificates.png) |

---

## 📋 Nội dung portfolio

| # | Mục | Mô tả |
|---|-----|-------|
| 01 | 🙋 **Giới thiệu** | Thông tin cá nhân, kỹ năng công nghệ, định hướng nghề nghiệp |
| 02 | 💻 **Dự án** | LTWINDOW11111, CTDL, LoL Analytics |
| 03 | 🏆 **Chứng chỉ** | Google Cloud, AWS, Mendix, Google AI — có link xác minh |
| 04 | 📬 **Liên hệ** | Email, GitHub, LinkedIn và form gửi tin nhắn |

---

## 🛠️ Công nghệ sử dụng

| Công nghệ | Mục đích |
|-----------|----------|
| HTML5 | Cấu trúc nội dung trang |
| CSS3 | Thiết kế, animation, responsive |
| JavaScript (ES6+) | Scroll effect, Intersection Observer |
| Google Fonts | Font Space Grotesk & Sora |
| GitHub Pages | Hosting & tự động deploy |

---

## 🚀 Quá trình thực hiện

### Bước 1 — Tạo Repository trên GitHub

```
1. Đăng nhập GitHub → New repository
2. Đặt tên repo: portfolio
3. Chọn Public, tick "Add a README file"
4. Nhấn Create repository
```

### Bước 2 — Clone về máy

```bash
git clone https://github.com/vuhuyminh5-arch/portfolio.git
cd portfolio
```

### Bước 3 — Xây dựng index.html

Trang gồm 4 section chính:

```
#hero          → Màn hình chào, tên & vai trò
#about         → Giới thiệu bản thân, danh sách kỹ năng
#projects      → Card từng dự án, link GitHub
#certificates  → Chứng chỉ kèm link xác minh Coursera/Mendix
#contact       → Thông tin liên lạc + form gửi tin nhắn
```

### Bước 4 — Push lên GitHub

```bash
git add .
git commit -m "feat: add portfolio website"
git push origin main
```

### Bước 5 — Bật GitHub Pages

```
Vào repo → Settings → Pages
→ Source: Deploy from a branch
→ Branch: main / (root)
→ Save
```

Sau ~2 phút, truy cập:  
`https://vuhuyminh5-arch.github.io/portfolio`

---

## 📁 Cấu trúc thư mục

```
portfolio/
├── index.html          # Toàn bộ website (HTML + CSS + JS)
├── README.md           # File mô tả này
└── screenshots/        # Ảnh chụp màn hình demo
    ├── hero.png
    ├── projects.png
    └── certificates.png
```

---

## 🏆 Chứng chỉ được đề cập

| Chứng chỉ | Tổ chức | Link xác minh |
|-----------|---------|---------------|
| Google Workspace User and Resource Management | Google Cloud · Coursera | [Xác minh](https://coursera.org/verify/1MDDR0HC9N5A) |
| Getting Started with AWS Generative AI for Developers | Amazon Web Services · Coursera | [Xác minh](https://coursera.org/verify/JJ9YZSP3BIX1) |
| Start Writing Prompts like a Pro | Google · Coursera | [Xác minh](https://coursera.org/verify/V9MYCHI1MEGV) |
| Introduction to AI | Google · Coursera | [Xác minh](https://coursera.org/verify/XU7KCU4BDEMY) |
| Mendix Rapid Developer Certification | Mendix · #108764 | — |

---

## 💻 Chạy local

```bash
# Cách 1: Mở trực tiếp file index.html trên trình duyệt

# Cách 2: VS Code Live Server
# Chuột phải index.html → Open with Live Server

# Cách 3: Python HTTP server
python -m http.server 8000
# Truy cập: http://localhost:8000
```

---

## 👤 Tác giả

**Vũ Huy Minh**  
Sinh viên Công nghệ Thông tin — Khoa CNTT  
Đại học Sư phạm TP.HCM (HCMUE)

- 📧 Email: [vuhuyminh5@gmail.com](mailto:vuhuyminh5@gmail.com)
- 💻 GitHub: [github.com/vuhuyminh5-arch](https://github.com/vuhuyminh5-arch)
- 🔗 LinkedIn: [linkedin.com/in/huyminh-](https://www.linkedin.com/in/huyminh-)

---

© 2026 Vũ Huy Minh · Built with ♥ in TP.HCM
