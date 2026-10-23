# BLADE & SOUL: AWAKENING &mdash; GAME LANDING PAGE
### Đồ Án Môn Học: Thiết Kế Web (Web Design)

[![HTML5](https://img.shields.io/badge/HTML5-Semantic-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Glossary/HTML5)
[![CSS3](https://img.shields.io/badge/CSS3-Variables%20%7C%20Flexbox%20%7C%20Grid-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Zero-JS](https://img.shields.io/badge/JavaScript-Zero%20JS%20(Pure%20CSS)-success)](#)
[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-brightgreen?logo=github)](https://bladeandsouls.github.io/Phat_HuynhMai_526000150/)

---

## 📌 THÔNG TIN SINH VIÊN & ĐỒ ÁN

- **Họ và tên:** Huỳnh Mai Phát
- **Mã số sinh viên (MSSV):** `526000150`
- **Tên Repository:** `Phat_HuynhMai_526000150`
- **Tài khoản GitHub:** [BladeAndSouls](https://github.com/BladeAndSouls)
- **Đường dẫn Repository:** [https://github.com/BladeAndSouls/Phat_HuynhMai_526000150](https://github.com/BladeAndSouls/Phat_HuynhMai_526000150)
- **Đường dẫn Live Demo (GitHub Pages):** [https://bladeandsouls.github.io/Phat_HuynhMai_526000150/](https://bladeandsouls.github.io/Phat_HuynhMai_526000150/)
- **Đề tài lựa chọn:** Landing Page giới thiệu Game MMORPG Võ Thuật Next-Gen (*Blade & Soul: Awakening*)

---

## 🌐 XEM TRỰC TIẾP GIAO DIỆN LIVE (LIVE DEMO)

👉 **Truy cập ngay:** **[https://bladeandsouls.github.io/Phat_HuynhMai_526000150/](https://bladeandsouls.github.io/Phat_HuynhMai_526000150/)**

> *(Đường dẫn trên cũng đã được đính kèm ở phần Mô tả (About/Website) của Repository theo đúng yêu cầu đề bài).*

---

## 🎯 ĐỐI CHIẾU TIÊU CHÍ KỸ THUẬT CỦA ĐỀ BÀI

### 1. Chuẩn Semantic HTML5 (Tối thiểu 5 thành phần)
Trang web sử dụng đúng ngữ nghĩa các thẻ chuẩn của HTML5 nhằm tối ưu khả năng đọc hiểu của công cụ tìm kiếm (SEO) và hỗ trợ công nghệ trợ năng:
- `<header>`: Phần đầu trang cố định (fixed header với blur glassmorphism), logo và các nút CTA.
- `<nav>`: Thanh điều hướng trang chính với các liên kết neo (anchor link) cuộn mượt mà.
- `<main>`: Khu vực bao gói toàn bộ nội dung chính của website.
- `<section>` & `<article>`: 
  - `<article class="lore-article">`: Khối bài viết cốt truyện thế giới khởi nguyên.
  - `<article class="class-card">`: Các thẻ phân loại thông tin từng hệ phái độc lập.
- `<footer>`: Chân trang với điều hướng phụ, thông tin bản quyền và khung định danh sinh viên.

### 2. Kỹ thuật CSS & CSS Variables
- **CSS Variables (`:root`):** Toàn bộ bảng màu Neon Cyber Fantasy (`--primary-color`, `--secondary-color`, `--accent-gold`), thang font chữ (`Cinzel`, `Montserrat`), bảng khoảng cách (`--space-*`) và bán kính bo viền (`--radius-*`) được quản trị tập trung tại đầu file `style.css`.
- **CSS Flexbox:** Dùng cho thanh điều hướng Header, phân bổ các nút CTA, căn chỉnh icon và số liệu thống kê.
- **CSS Grid:** Dùng cho hệ thống thẻ Hero 2 cột, lưới Hệ phái co giãn thông minh (`repeat(auto-fit, minmax(270px, 1fr))`), lưới Tính năng 2x2, lưới Gói game 3 cột và Bảng so sánh cấu hình PC.
- **Responsive hoàn chỉnh:** Đảm bảo hiển thị hoàn hảo từ màn hình di động nhỏ (360px), máy tính bảng (768px) đến màn hình máy tính để bàn độ phân giải cao (1920px+).

### 3. Tương tác & Hiệu ứng (Libraries & Pure CSS)
- **Hệ thống 4 Thần Khí Võ Học (Pure CSS Multi-Theme Switcher):**
  - **Thanh Long (Mặc định):** Phối màu Hàn Băng & Kiếm Khí (Cyan & Deep Cosmic Indigo).
  - **Xích Hỏa:** Phối màu Liệt Diễm & Ma Kiếm (Crimson Flame & Burning Amber).
  - **U Minh:** Phối màu Ám Ảnh & Ma Hoàng (Shadow Void & Electric Violet).
  - **Hoàng Kim:** Phối màu Thiên Triều & Thần Thánh (Imperial Celestial Gold).
  - *Cơ chế hoạt động:* Tận dụng bộ chọn CSS hiện đại `:has(#theme-*:checked)` và Sibling Combinator `#theme-*:checked ~ .site-wrapper` để chuyển đổi tức thì toàn bộ biến CSS trên website mà **hoàn toàn không dùng JavaScript**.
  - Tích hợp 2 bộ điều khiển trực quan: Thanh chuyển nhanh trên Navigation Header và Dock Thần Khí nổi (Floating Theme Dock) tiện dụng.
- **Bộ hiệu ứng thị giác phong cách Kiếm Hiệp:**
  - **Kiếm Trận Cổ Đại (Rotating Dragon Rune Array):** Ma trận phong ấn xoay đồng tâm đa lớp huyền ảo phía sau nhân vật chính.
  - **Khí Huyết Tàn Ảnh (Ambient Floating Embers):** Các đốm chân khí lơ lửng bay từ chân trang lên tạo chiều sâu không gian.
  - **Vệt Trảm Kiếm (Sword Slash Beam):** Hiệu ứng đường chém kiếm quang quét chéo cực nhanh khi rê chuột (:hover) vào bất kỳ thẻ hệ phái, tính năng hay gói quà nào.
  - **Tiêu Đề Ánh Kim (Metallic Sword Gleam):** Ánh chớp kim loại quét tuần hoàn ngang qua dòng chữ tiêu đề.
  - **Vòng Xung Kích Năng Lượng (CTA Energy Pulse Ring):** Sóng năng lượng tỏa nhịp nhàng quanh các nút kêu gọi hành động.
- **Tích hợp Animate.css:** Nhúng CDN chính thức, sử dụng các hiệu ứng `animate__fadeInDown`, `animate__fadeInUp`, `animate__zoomIn`, `animate__pulse`, `animate__infinite` cho các thành phần mở đầu Hero.
- **Tích hợp AOS (Animate On Scroll) theo chuẩn "Không dùng JavaScript":**
  - Mọi section và card đều có đầy đủ thuộc tính `data-aos="fade-up"`, `data-aos="zoom-in"`, `data-aos-delay`.
  - Được hỗ trợ bởi công nghệ hiện đại **Pure CSS Scroll-Driven Animations** (`@supports (animation-timeline: view())`) và fallback mượt mà, giúp các khối nội dung xuất hiện sinh động khi cuộn trang mà tuyệt đối không cần tới JavaScript.
- **Hiệu ứng `:hover` & `:focus`:** Tự viết 100% bằng CSS:
  - Hiệu ứng quét tia sáng (shimmer light sweep) cho nút bấm chính.
  - Hiệu ứng nâng thẻ 3D (`translateY(-10px)`) và viền hào quang neon khi rê chuột vào card hệ phái và gói quà.
  - Trạng thái `:focus-visible` với vòng neon bao quanh cho người dùng duyệt web bằng bàn phím (Accessibility).

### 4. Ràng buộc quan trọng: "Không sử dụng JavaScript"
- **Không có bất kỳ thẻ `<script>` hay file `.js` nào.**
- Toàn bộ Theme Switcher, Menu điều hướng Mobile (Hamburger) và các hiệu ứng động được hiện thực 100% bằng **HTML5 & CSS3 thuần**.

---

## 📂 CẤU TRÚC THƯ MỤC REPOSITORY

```text
Phat_HuynhMai_526000150/
├── index.html                   # File mã nguồn HTML chính (Chuẩn Semantic HTML5)
├── style.css                    # File CSS chính (CSS Variables, Flexbox, Grid, Pure CSS Animations)
├── PROMPT_LOG.md                # Nhật ký Prompt Engineering chi tiết các bước thực hiện
├── README.md                    # Tài liệu hướng dẫn đồ án và link live demo
└── assets/                      # Thư mục tài nguyên đa phương tiện độc lập
    ├── images/                  # Thư mục hình ảnh Vector SVG chất lượng cao
    │   ├── logo.svg             # Logo thương hiệu Blade & Soul: Awakening
    │   ├── hero-bg.svg          # Background không gian vũ trụ kiếm hiệp
    │   ├── char-blade-master.svg# Minh họa thẻ Kiếm Sư
    │   ├── char-force-master.svg# Minh họa thẻ Khí Công Sư
    │   ├── char-assassin.svg    # Minh họa thẻ Sát Thủ
    │   ├── char-soul-fighter.svg# Minh họa thẻ Quyền Sư
    │   ├── feature-combat.svg   # Minh họa Không chiến & Combo
    │   ├── feature-world.svg    # Minh họa Khinh công thế giới mở
    │   ├── feature-pvp.svg      # Minh họa Đấu trường Esports
    │   └── feature-graphics.svg # Minh họa Unreal Engine 5 Next-Gen
    └── icons/                   # Thư mục icon SVG giao diện (Kiếm, Khiên, Tải về, Play,...)
        ├── sword.svg
        ├── shield.svg
        ├── download.svg
        ├── play.svg
        ├── check.svg
        ├── trophy.svg
        └── cpu.svg
```

---

## 🚀 HƯỚNG DẪN KÍCH HOẠT GITHUB PAGES

Nếu Giảng viên hoặc người xem muốn tự kích hoạt lại GitHub Pages trên nhánh `main`:

1. Truy cập vào kho lưu trữ: `https://github.com/BladeAndSouls/Phat_HuynhMai_526000150`
2. Nhấp vào tab **Settings** (Cài đặt) ở thanh điều hướng trên cùng của kho lưu trữ.
3. Ở menu bên trái, nhấp vào mục **Pages** (dưới nhóm *Code and automation*).
4. Tại mục **Build and deployment**:
   - **Source:** Chọn `Deploy from a branch`.
   - **Branch:** Chọn nhánh `main` và thư mục `/ (root)`.
   - Nhấp nút **Save**.
5. Đợi khoảng 1-2 phút, GitHub sẽ hiển thị đường link trang web trực tiếp:  
   👉 `https://bladeandsouls.github.io/Phat_HuynhMai_526000150/`
6. Sao chép liên kết này và dán vào phần **About -> Website** ở trang chủ Repository để giảng viên xem nhanh.

---

## 💻 HƯỚNG DẪN CHẠY VÀ KIỂM THỬ LOCAL

Vì dự án được xây dựng hoàn toàn bằng **HTML5 & CSS3 thuần (Zero JavaScript)**, bạn có thể chạy thử nghiệm tức thì mà không cần cài đặt bất kỳ công cụ môi trường hay dependency nào:

1. **Cách 1: Mở trực tiếp**
   - Tải kho lưu trữ về máy hoặc clone qua lệnh:
     ```bash
     git clone https://github.com/BladeAndSouls/Phat_HuynhMai_526000150.git
     ```
   - Nhấp đúp chuột trực tiếp vào file `index.html` để mở trên trình duyệt bất kỳ (Chrome, Edge, Firefox, Safari).

2. **Cách 2: Sử dụng VS Code Live Server (Tùy chọn)**
   - Mở thư mục dự án bằng Visual Studio Code.
   - Cài đặt tiện ích mở rộng **Live Server** (Ritwick Dey).
   - Nhấp chuột phải vào `index.html` và chọn **Open with Live Server**.

---

© 2026 **Huỳnh Mai Phát (MSSV: 526000150)**. Bản quyền đồ án môn Thiết Kế Web.