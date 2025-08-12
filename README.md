# 🛒 BTC Walmart

เว็บไซต์จำลองร้านค้าออนไลน์ที่รองรับการชำระเงินด้วย Bitcoin  
สร้างด้วย HTML, CSS, JavaScript และ Firebase

---

## 🔧 ฟีเจอร์หลัก

- แสดงสินค้าและราคาที่แปลงเป็น BTC
- เพิ่มสินค้าลงตะกร้า (ใช้ localStorage)
- ระบบสมาชิก (สมัคร / เข้าสู่ระบบ) ด้วย Firebase Authentication
- หน้าสำหรับแอดมินเพิ่มสินค้าใหม่ (เชื่อม Firestore)
- ดีไซน์แบบ Dark Mode สไตล์ Crypto

---

## 📁 โครงสร้างไฟล์
├── index.html ├── products.html ├── cart.html ├── login.html ├── register.html ├── admin.html ├── style.css ├── firebase-config.js └── README.md

---

## 🚀 วิธีติดตั้ง

1. สร้างโปรเจกต์ Firebase ที่ [console.firebase.google.com](https://console.firebase.google.com)
2. เปิดใช้งาน Authentication (Email/Password)
3. เปิดใช้งาน Firestore Database
4. คัดลอกค่าคอนฟิกจาก Firebase มาใส่ใน `firebase-config.js`
5. เปิดไฟล์ `index.html` ด้วยเบราว์เซอร์ หรือ deploy ด้วย GitHub Pages / Firebase Hosting

---

## 📦 การ deploy ด้วย Firebase Hosting

```bash
npm install -g firebase-tools
firebase login
firebase init
# เลือก Hosting และเชื่อมกับโปรเจกต์
firebase deploy


---

📜 License
MIT License — ใช้เพื่อการศึกษาและทดลองเท่านั้น

ไฟล์นี้ช่วยให้โปรเจกต์ดูเป็นมืออาชีพและพร้อมแชร์หรือพัฒนาเพิ่มเติม  
ต่อไปคุณอยากได้ไฟล์สุดท้ายแล้วใช่ไหมครับ — `firebase-config.js`? 😄
