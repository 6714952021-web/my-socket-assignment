# รายงานแบบฝึกหัด Socket API & Docker (Assignment 1 & 2)

**ข้อมูลผู้จัดทำ**
* ชื่อ-นามสกุล: นายศุภวิชญ์ กิจไพศาลศักดิ์
* รหัสนักศึกษา: 6714952021
* กลุ่ม/เซคชัน: 2

---

## 🛠️ แบบฝึกหัดที่ 1: ระบบ Chat ด้วย Docker (2 Clients & 1 Server)

### คำอธิบายการทำงาน
ระบบแชทนี้ประยุกต์ใช้ Socket API แบบ TCP ในการส่งข้อมูลระหว่าง Client 2 ตัว ผ่าน Server กลาง โดยรันอยู่ในรูปแบบของ Docker Multi-container และใช้ Docker Compose ในการจัดการ

### รูปการทำงานของ code
<img width="1919" height="1031" alt="Screenshot 2026-11-27 111824" src="https://github.com/user-attachments/assets/c7a7c1a9-511c-41bc-a713-5a89c65871cc" />

## 🌐 แบบฝึกหัดที่ 2: เว็บแอปพลิเคชัน Flask และ Socket Server

### คำอธิบายการทำงาน
แอปพลิเคชันหน้าเว็บพัฒนาด้วย Flask รับข้อความผ่านการกดส่งฟอร์ม (POST Method) จากนั้น Flask จะทำหน้าที่เป็น Client ส่งข้อความนั้นต่อไปยัง Socket Server เพื่อทำการสะท้อนข้อมูลกลับ (Echo) และแสดงผลบนหน้าเว็บ

### รูปการทำงานของ code
<img width="1918" height="990" alt="Screenshot 2026-11-27 112821" src="https://github.com/user-attachments/assets/cc666ca7-b739-43f8-918e-718a6ea9fd3f" />
