# MoneyFlow 💸

เว็บแอปรายรับ-รายจ่ายแบบ Responsive/PWA สำหรับ GitHub Pages ใช้งานได้ทั้งมือถือ แท็บเล็ต และคอมพิวเตอร์

## เปิดใช้งานบน GitHub Pages

1. สร้าง Repository ใหม่ใน GitHub เช่น `moneyflow`.
2. อัปโหลดไฟล์และโฟลเดอร์ทั้งหมดจากชุดนี้ไว้ที่ **root ของ repository** โดยให้ `index.html` อยู่ระดับบนสุด.
3. ไปที่ **Settings → Pages**.
4. ใน **Build and deployment** เลือก **Deploy from a branch**.
5. Branch เลือก **main** และ Folder เลือก **/(root)** แล้วกด **Save**.
6. รอสถานะ GitHub Pages แสดง URL เว็บไซต์ จากนั้นเปิด URL นั้นบนมือถือได้เลย.

## ติดตั้งบนหน้าจอมือถือ

- Android / Chrome: เปิดเว็บ → เมนู ⋮ → **Add to Home screen / Install app**
- iPhone / Safari: เปิดเว็บ → Share → **Add to Home Screen**

## การเก็บข้อมูล

ข้อมูลรายการและเป้าหมายเก็บใน `localStorage` ของเบราว์เซอร์บนอุปกรณ์นั้น ๆ ดังนั้นข้อมูล **ไม่ซิงก์ข้ามมือถือ/คอมพิวเตอร์โดยอัตโนมัติ**. ใช้เมนูสำรองข้อมูล JSON เพื่อย้ายหรือเก็บสำรองข้อมูลได้.

หลังเปิดเว็บออนไลน์ครั้งแรก Service Worker จะช่วยให้ตัวแอปเปิดใช้งานออฟไลน์ได้ในเบราว์เซอร์ที่รองรับ.
