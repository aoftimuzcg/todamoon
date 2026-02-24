# 🎁 Gift Survey

ระบบสำรวจความต้องการของขวัญ — พร้อม deploy บน Vercel

## วิธี Deploy บน Vercel

### วิธีที่ 1: Drag & Drop (ง่ายที่สุด)
1. แตกไฟล์ ZIP นี้ออกมา
2. ไปที่ https://vercel.com/new
3. ลาก **folder** `gift-survey-vercel` ใส่หน้า Vercel
4. กด Deploy → รับ URL ทันที!

### วิธีที่ 2: Vercel CLI
```bash
npm i -g vercel
cd gift-survey-vercel
vercel
```

## ตั้งค่า Firebase
แก้ไฟล์ `index.html` บรรทัด `window.FIREBASE_CONFIG`:
```js
window.FIREBASE_CONFIG = {
  apiKey: "your-api-key",
  databaseURL: "https://your-project-default-rtdb.firebaseio.com",
  ...
}
```

## ลิ้งค์
- **ผู้ตอบแบบสำรวจ:** `yoursite.vercel.app/#survey`
- **Admin / ดูผล:** `yoursite.vercel.app`
