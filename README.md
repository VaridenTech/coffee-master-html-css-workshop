# ☕ Coffee Master UI — HTML & CSS Workshop

โค้ดฉบับสมบูรณ์ของหน้าเว็บร้านกาแฟ **Coffee Master** ที่สร้างด้วย HTML และ CSS ล้วน (ไม่มี JavaScript)

- `index.html` — โครงสร้างหน้าเว็บ: header, hero, Our Coffee, Menu, Order และ footer
- `style.css` — การจัดวางด้วย Flexbox และ Grid, แก้วกาแฟที่วาดด้วย CSS และ responsive ที่ 900px / 600px

## เปิดดู

ดาวน์โหลดหรือ clone repo นี้ แล้วดับเบิลคลิก `index.html` เพื่อเปิดในเบราว์เซอร์ ไม่ต้องติดตั้งอะไรเพิ่ม

```sh
git clone https://github.com/VaridenTech/coffee-master-html-css-workshop.git
```

## เปรียบเทียบกับงานของคุณ

```sh
diff coffee-master-ui/index.html coffee-master-html-css-workshop/index.html
diff coffee-master-ui/style.css coffee-master-html-css-workshop/style.css
```

ข้อมูลเมนู จำนวน และยอดรวมเป็นข้อมูลตัวอย่างที่เขียนไว้ใน HTML ปุ่ม `+` / `-` และ Place Order จึงยังไม่ทำงาน

## Workshop JavaScript

Workshop ถัดไปจะต่อยอดหน้านี้ด้วย Vanilla JavaScript ให้ปุ่ม `+` / `-` และ Place Order ทำงานจริง โค้ดเริ่มต้น (`start_js/`) และเฉลย (`finish_js/`) อยู่ที่ branch `javascript` ของ repo นี้

```sh
git clone -b javascript https://github.com/VaridenTech/coffee-master-html-css-workshop.git coffee-master-javascript
```
