# โปรแกรมบันทึกรายรับ-รายจ่ายส่วนบุคคล

Static Web App สำหรับ GitHub Pages ใช้ HTML, CSS, Vanilla JavaScript และ Chart.js

## ติดตั้งบน GitHub Pages
1. สร้าง Repository ใหม่บน GitHub
2. อัปโหลด `index.html`, `style.css`, `script.js` ไว้ที่ root ของ branch `main`
3. ไปที่ Settings > Pages
4. Build and deployment เลือก `Deploy from a branch`
5. Branch เลือก `main` และ Folder เลือก `/ (root)` แล้ว Save

## การจัดเก็บข้อมูล
ข้อมูลอยู่ใน LocalStorage ของ Browser/Device ที่ใช้งาน ไม่ซิงก์ข้ามเครื่อง และการล้าง Site Data จะทำให้ข้อมูลหาย

## หมายเหตุ
Chart.js, Font Awesome และ Google Fonts โหลดผ่าน CDN จึงต้องเชื่อมต่ออินเทอร์เน็ตในการโหลดครั้งแรก
