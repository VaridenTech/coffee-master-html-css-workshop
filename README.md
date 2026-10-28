# ☕ Coffee Master Order App — JavaScript Workshop

โค้ดสำหรับ Workshop **Coffee Master: สร้างระบบสั่งกาแฟด้วย Vanilla JavaScript** ต่อยอดจากหน้าเว็บ HTML & CSS (branch `main`) ด้วย JavaScript ล้วน ไม่ใช้ framework ไม่ต้องติดตั้ง Node.js

- `start_js/` — จุดเริ่มต้น `index.html` และ `src/style.css` เขียนไว้ให้แล้ว ส่วน `src/main.js` ยังว่าง เราจะเขียนที่นี่
- `finish_js/` — เฉลยฉบับสมบูรณ์ ไว้เทียบคำตอบหลังเขียนเสร็จ หรือเมื่อติดปัญหา

```
start_js/
├── index.html        # โครง HTML (มีให้แล้ว)
└── src/
    ├── main.js       # ไฟล์ว่าง ← เราจะเขียนที่นี่
    └── style.css     # CSS ทั้งหมด (มีให้แล้ว)

finish_js/            # โครงสร้างเดียวกัน แต่ main.js เขียนครบแล้ว
```

## Features ของแอปที่เสร็จแล้ว

- แสดงเมนูกาแฟ/เบเกอรี่พร้อมราคาและคำอธิบาย
- เพิ่ม/ลดจำนวนสินค้าในตะกร้าด้วยปุ่ม `+` / `-`
- คำนวณ Subtotal, Tax (7%) และ Total แบบ real-time
- กรอกชื่อลูกค้าและกดสั่งซื้อ พร้อม validation (ต้องกรอกชื่อ และเลือกอย่างน้อย 1 รายการ)
- แสดงข้อความแจ้งเตือน/สำเร็จหลังกดสั่งซื้อ

## เริ่มต้น

Clone เฉพาะ branch `javascript`:

```sh
git clone -b javascript https://github.com/VaridenTech/coffee-master-html-css-workshop.git coffee-master-javascript
```

หรือถ้า clone repo ไว้แล้ว:

```sh
git checkout javascript
```

จากนั้น:

1. เปิด VS Code แล้วเลือก **File → Open Folder…** เลือกโฟลเดอร์ `start_js/` (ต้องเปิดทั้งโฟลเดอร์ ไม่ใช่เปิดไฟล์เดียว)
2. คลิกขวาที่ `index.html` แล้วเลือก **Open with Live Server** (หรือกดปุ่ม Go Live ที่มุมขวาล่าง)
3. เริ่มเขียนโค้ดใน `src/main.js`

> `index.html` อ้างไฟล์ด้วย path แบบ relative (เช่น `./src/style.css`) จึงดับเบิลคลิกเปิดตรง ๆ ก็ได้ แต่แนะนำ Live Server เพราะจะรีเฟรชหน้าเว็บให้อัตโนมัติทุกครั้งที่กด save

## เปรียบเทียบกับเฉลย

เปิดโฟลเดอร์รากของ repo ใน Terminal แล้วรัน:

```sh
diff start_js/src/main.js finish_js/src/main.js
```

หรือใน VS Code คลิกขวาที่ `start_js/src/main.js` เลือก **Select for Compare** แล้วคลิกขวาที่ `finish_js/src/main.js` เลือก **Compare with Selected**

## Workshop HTML & CSS

ส่วน HTML และ CSS ของหน้าเว็บนี้สอนแยกไว้ใน Workshop HTML & CSS โค้ดฉบับสมบูรณ์อยู่ที่ branch `main` ของ repo นี้ ใครทำ Workshop นั้นมาแล้วจะได้หน้าเว็บเหมือนใน `start_js/` ทุกประการ
