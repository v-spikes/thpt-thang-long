# THPT Thang Long project

A static website celebrating the culture, people, cuisine, and historical landmarks of Hanoi, Vietnam. Created as a school project for my friends.

---

## Overview

The site tells the story of Hanoi thru four tabs:

| Page | Content |
|------|---------|
| **Home** (`index.html`) | Introduction to Hanoi's 1,000-year history, from the founding of Thăng Long in 1010 to the present-day capital |
| **People** (`con-nguoi.html`) | The character of Hanoians: elegance, depth, warmth, a love of learning, and the art of subtle speech |
| **Cuisine** (`am-thuc.html`) | Three iconic Hanoi foods: Phở Thìn 13 Lò Đúc, Cốm Làng Vòng, and Cafe Giảng |
| **Historical Sites** | Hồ Hoàn Kiếm (`di-tich/ho-hoan-kiem.html`) and Văn Miếu Quốc Tử Giám (`di-tich/van-mieu.html`) |

---

## Project Structure

```
thpt-thang-long/
├── index.html          # Home page
├── con-nguoi.html      # People of Hanoi
├── am-thuc.html        # Hanoi cuisine
├── di-tich/
│   ├── ho-hoan-kiem.html   # Hoan Kiem Lake
│   └── van-mieu.html       # Temple of Literature
└── img/                # All images and assets
```

---

## Running Locally

No build step is needed. Just open `index.html` in any modern browser:

```bash
# Option 1 — open directly
start index.html

# Option 2 — serve with Python for correct relative paths
python -m http.server 8080
# then visit http://localhost:8080
```

---

## Credits:

Permission approved by members of [12QT3](https://www.instagram.com/qt3nana/)
