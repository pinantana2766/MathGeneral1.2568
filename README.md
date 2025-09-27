# Student Scores - คณิตศาสตร์ทั่วไป

เว็บระบบแสดงผลคะแนนนักศึกษา + Admin Panel พร้อมระบบ Login จริงจากไฟล์ users.csv

## 📌 วิธีใช้งาน

### 1. ใช้บนเครื่อง (Offline)
- แตกไฟล์ออก จะมี `index.html`, `users.csv`, `scores_example.csv`
- เปิด `index.html` ด้วย Browser (Chrome/Firefox/Edge)
- กดเลือก `users.csv` ก่อนเข้าสู่ระบบ
- ใส่รหัสผู้ใช้/รหัสผ่านตามใน `users.csv`

### 2. บัญชีตัวอย่าง
- **Admin** → user: `admin001` / pass: `1234`
- **Student** → user: `6401234567` / pass: `abcd`
- **Student** → user: `6401234568` / pass: `efgh`

### 3. ฟีเจอร์
- **Admin**: อัปโหลด/แก้ไขคะแนน, Import CSV, Export CSV
- **Student**: ดูผลคะแนนของตนเอง

### 4. Deploy GitHub Pages
1. สร้าง Repository บน GitHub
2. อัปโหลดไฟล์ทั้งหมด (`index.html`, `users.csv`, `scores_example.csv`)
3. ไปที่ **Settings → Pages**
4. เลือก Branch `main` และโฟลเดอร์ `/root`
5. จะได้ลิงก์ออนไลน์ใช้งานได้เลย

---
> ตัวอย่างพัฒนาโดย ChatGPT (OpenAI)
