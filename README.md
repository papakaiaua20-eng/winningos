# Pex JobSlayer — Vercel + Gemini API

โปรเจกต์นี้เป็นเว็บ Static สำหรับ Deploy บน Vercel

## วิธีใช้งาน
1. Deploy โฟลเดอร์นี้ขึ้น Vercel
2. เปิดหน้าเว็บ
3. กดไอคอน ⚙️
4. กรอก Gemini API Key ของผู้ใช้เอง
5. กดตั้งค่า แล้วเริ่มใช้งาน

API Key ถูกเก็บใน `localStorage` ของเบราว์เซอร์ในชื่อ:
`pex-jobslayer-gemini-key`

เว็บเรียก Gemini API จากฝั่ง Browser โดยตรง และไม่ได้ฝังคีย์ของเจ้าของโปรเจกต์ไว้ในโค้ด

## สำคัญ
ผู้ใช้แต่ละคนต้องใส่ API Key ของตัวเอง และการใช้งาน Gemini จะคิดตามสิทธิ์/โควตาของ API Key นั้น
