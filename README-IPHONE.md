# iPhone UX/UI Update
1. นำ iphone.css ไปไว้ข้าง style.css
2. ใน index.html เพิ่มบรรทัดนี้ต่อจาก style.css:
   <link rel="stylesheet" href="iphone.css">
3. ตรวจว่า viewport เป็น:
   <meta name="viewport" content="width=device-width,initial-scale=1,viewport-fit=cover">
4. อัปโหลด index.html, style.css, iphone.css และ script.js ไป GitHub Pages

ปรับปรุง: Safe Area, Dynamic Island, Home Indicator, touch target 44px, input 16px ป้องกัน Safari zoom, Portrait/Landscape และ toast/modal บน iPhone
