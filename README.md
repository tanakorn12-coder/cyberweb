# 🛡️ พักเช็ก (PakCheck) - AI Scam Guard

> **พัก 10 วิ เช็กให้ชัวร์ ก่อนโอนหรือกดลิงก์**  
> แพลตฟอร์มคุ้มครองความปลอดภัยดิจิทัลเพื่อผู้สูงวัยและครอบครัวไทย (Cross-Generational Cyber Guard)

---

## 🌐 เข้าใช้งานระบบ (Live Demo & Online Sites)

- 📱 **ระบบจำลองหน้าจอมือถือหลายรุ่น (Multi-Device Simulator)**: [https://tanakorn12-coder.github.io/cyberweb/simulator.html](https://tanakorn12-coder.github.io/cyberweb/simulator.html)
- 🖥️ **หน้าเว็บหลัก (Desktop Web)**: [https://tanakorn12-coder.github.io/cyberweb/](https://tanakorn12-coder.github.io/cyberweb/)
- 💻 **GitHub Repository**: [https://github.com/tanakorn12-coder/cyberweb](https://github.com/tanakorn12-coder/cyberweb)

---

## 📱 สถาปัตยกรรม 2 ระบบ: เว็บไซต์ vs โทรศัพท์มือถือ & LINE OA (UX/UI Comparative Architecture)

| มิติการเปรียบเทียบ | 🖥️ หน้าจอเว็บไซต์ (Desktop Web) | 📱 โทรศัพท์มือถือ & LINE OA (Mobile Frontline) |
| :--- | :--- | :--- |
| **บทบาทหลัก** | **Family Command Center (ศูนย์บัญชาการข้อมูล)** | **Frontline Real-time Guard (เกราะป้องกันด่านหน้า)** |
| **กลุ่มผู้ใช้งาน** | ลูกหลาน, ผู้ดูแลครอบครัว, หรือผู้สูงวัยที่นั่งโต๊ะตรวจละเอียด | ผู้สูงวัย คุณตา คุณยาย ขณะถือมือถือ หรือกำลังคุยสาย |
| **พฤติกรรมการใช้งาน** | นั่งตรวจสอบข้อมูล ค้นประวัติ Blacklist กรอกฟอร์ม พิมพ์ PDF | แตะปุ่มรับสาย เผลอกดลิงก์ หรือได้รับข้อความทาง LINE |
| **ปรัชญา UX/UI** | Multi-column, Data Tables, Comprehensive Verification | **Zero-Typing (ไม่ต้องพิมพ์)**, ปุ่มขนาดใหญ่พิเศษ 60-80px (Thumb Zone), อ่านออกเสียง |
| **จุดเด่นเฉพาะระบบ** | บันทึกเลขเคสธนาคาร (Bank Case ID), ลิงก์แจ้งความ ตร., พิมพ์เอกสารสรุปคดี | **Active Call Banner** เตือนภัยขณะคุยสาย, **LINE Oversized Rich Menu**, AI Scan ในแชต |

---

## 📄 โครงสร้างไฟล์ในระบบ (System Structure)

### 🖥️ หน้าจอหลักเว็บไซต์ (Desktop Web Suite)
1. `index.html` — หน้าแรก: เครื่องมือตรวจด่วน 3 ช่องทาง (เบอร์โทร, สลิป/แชต, SMS/ลิงก์) + สัญญาณไฟ 3 สี
2. `safe-step.html` — SAFE STEP: ตัวช่วยวิเคราะห์ประเมินสถานการณ์ทีละขั้น + Do's & Don'ts
3. `support-radar.html` — สะกิดครอบครัว: ส่งสรุปเข้า LINE ลูกหลาน (Consent-First) + เรดาร์เตือนภัยชุมชน
4. `emergency-guide.html` — คู่มือกู้ชีพ 1441: เบอร์โทรอายัด 8 ธนาคาร, เช็กลิสต์หลักฐาน, แจ้งความ ตร. ออนไลน์

### 📱 ระบบจำลองมือถือ (Device Simulator Suite)
5. `simulator.html` — ศูนย์ควบคุมการจำลองโทรศัพท์มือถือ:
   - เลือกรุ่น: **iPhone 16/17 Pro**, **Samsung S24 Ultra**, **มือถือโหมดผู้สูงวัย**, **iPad/Tablet**, **Responsive Frame**
   - ควบคุม: ปรับขนาดซูม (75%, 85%, 100%, 115%), หมุนหน้าจอ (Portrait / Landscape)
   - สลับหน้าจอสถานการณ์มือถือ & LINE ได้ 8+ หน้าจอจริง

### 📲 ไฟล์หน้าจอมือถือจำลอง (`/mobile/`)
- `mobile/home-call-banner.html` — หน้าจอหลักมือถือ + แบนเนอร์สายเข้าเตือนภัย + วิดเจ็ต AOC 1441
- `mobile/safe-step-mobile.html` — SAFE STEP คัดกรองภัยบนมือถือ การ์ดสัมผัสขนาดใหญ่
- `mobile/urgent-warning-mobile.html` — สัญญาณเตือนภัยสีแดง ห้ามโอนเงิน พร้อมเสียงเตือน
- `mobile/family-call-mobile.html` — ปุ่มแตะโทรหาลูกหลานด่วน และส่งบัตรเตือนเข้า LINE
- `mobile/line-chat-list.html` — หน้ารวมแชต LINE ปักหมุดบัญชีทางการพักเช็ก
- `mobile/line-official-account.html` — LINE Official Account พร้อม Oversized Rich Menu ยักษ์
- `mobile/line-ai-scan.html` — LINE AI Multimodal Scan วิเคราะห์ตราประทับ/เอกสารราชการปลอม
- `mobile/line-flex-message.html` — การ์ดผลตรวจ Flex Message สีแดง พร้อมปุ่มส่งต่อให้ลูกหลาน

---

## 🛠️ เทคโนโลยีที่ใช้ (Tech Stack)

- **Pure HTML5 / Modern CSS** (Zero-build overhead)
- **Tailwind CSS CDN**
- **Material Symbols Outlined** (Google Icons)
- **Be Vietnam Pro & Kanit Fonts**
- **Web Speech API** (Thai Text-to-Speech)
- **GitHub Pages** สำหรับ Continuous Deployment

---

*© 2025 พักเช็ก (PakCheck) — แพลตฟอร์มคุ้มครองความปลอดภัยดิจิทัลเพื่อประชาชนไทย*
