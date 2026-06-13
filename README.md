# แผนเกษียณ 45 ปี 🇹🇭 — PWA

## วิธีติดตั้งบน Android (3 ขั้นตอน)

### ขั้นที่ 1: Deploy ขึ้น Netlify (ฟรี)
1. ไปที่ https://app.netlify.com/drop
2. ลาก folder นี้ทั้ง folder ไปใส่ในหน้าเว็บ
3. รอ 10–30 วินาที → ได้ URL เช่น https://xxxxxx.netlify.app

### ขั้นที่ 2: เปิดบน Android
1. เปิด Chrome บน Android
2. พิมพ์ URL ที่ได้จาก Netlify

### ขั้นที่ 3: ติดตั้งเป็น App
1. แตะ ⋮ (เมนู 3 จุด) ที่มุมขวาบน
2. เลือก "Add to Home screen" หรือ "ติดตั้งแอป"
3. กด "Install" / "ติดตั้ง"
4. ได้ icon บน Home Screen เปิดได้เหมือน App จริง!

## ทางเลือกอื่น (ถ้าไม่อยากใช้ Netlify)
- GitHub Pages: push ไฟล์เหล่านี้ขึ้น GitHub repo → เปิด Pages
- Vercel: vercel.com/new → import project
- ใช้เป็น Local: รัน `npx serve .` แล้วเปิดที่ localhost:3000

## หมายเหตุ
- ใช้งานออฟไลน์ได้หลังจากเปิดครั้งแรก (Service Worker caches everything)
- ไม่มีการส่งข้อมูลไปไหน ทำงาน 100% บนเครื่องคุณ
