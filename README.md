# 🍨 Gelato POS & Management System

ระบบบริหารจัดการร้านไอศกรีมเจลาโต (Gelato Shop POS & Back-office ERP Prototype)  
พัฒนาด้วย Vue 3, Tailwind CSS และ Phosphor Icons ทำงานแบบ Single Page Application (SPA)

## ✨ ฟีเจอร์หลัก (Key Features)
- 🛒 **ระบบขายหน้าร้าน (POS Terminal)**: ปรับแต่งสกู๊ป, ภาชนะ (ถ้วย/โคน), ท็อปปิ้ง, ค้นหา/สมัครสมาชิก
- 💵 **ชำระเงินได้ 3 รูปแบบ**: เงินสด (คำนวณเงินทอน), ดิจิทัล QR PromptPay, บัตรเครดิต/เดบิต (จำลองเครื่อง EDC)
- 🧾 **พิมพ์ใบเสร็จความร้อน (Thermal Receipt Slip)**: รองรับการสั่งพิมพ์จริงผ่าน `window.print()`
- 📦 **ระบบคลังสต็อก (Inventory Management)**: ตัดสต็อกอัตโนมัติแยกสาขา (พารากอน, อารีย์, เซ็นทรัลเวิลด์), แจ้งเตือนของใกล้หมด (Low Stock Alert), เติม/ลด/ลบสต็อก
- 🏷️ **โปรโมชั่นและส่วนลด**: เลือกรหัสโปรโมชั่นคำนวณส่วนลดท้ายบิลแบบ Real-time
- 📊 **แดชบอร์ดผู้จัดการ (Manager Analytics)**: สรุปยอดขาย, สัดส่วนวิธีชำระเงิน, เปรียบเทียบผลประกอบการระหว่างสาขา
- 👥 **ระบบสิทธิ์และการจัดการผู้ใช้ (RBAC & Account Management)**: แยกสิทธิ์ `@manager` (เข้าถึงครบ 5 แท็บ) และ `@staff` (เข้าถึง 3 แท็บ)

## 🚀 Deployment on Cloudflare Pages
1. เชื่อมต่อ Git Repository กับ **Cloudflare Pages**
2. ตั้งค่าการ Deploy:
   - **Framework preset**: None
   - **Build command**: (ปล่อยว่าง)
   - **Build output directory**: `/` (หรือ root directory)
