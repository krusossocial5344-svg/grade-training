# สไลด์อบรมการใช้ระบบตัดเกรด (ครูผู้สอน)

เว็บสไลด์ไฟล์เดียว (ไม่ต้อง build ไม่ต้องติดตั้งอะไร) 24 หน้า ธีมแดง-ทอง
พัฒนาโดย ครูซอสสอนสังคม · โรงเรียนวัดบางปูน

## วิธีเอาขึ้น GitHub + Vercel (ทีละขั้น)

### A. อัปโหลดขึ้น GitHub
1. เข้า github.com แล้วกด New (สร้าง repository ใหม่) ตั้งชื่อ เช่น `grade-training` เลือก Public หรือ Private ก็ได้ กด Create repository
2. กด "uploading an existing file" (หรือ Add file → Upload files)
3. แตกไฟล์ zip บนเครื่อง แล้วลาก `index.html`, `vercel.json`, `README.md` และโฟลเดอร์ `images` ทั้งโฟลเดอร์ ขึ้นไปวางพร้อมกัน
4. รอจนขึ้นครบทุกไฟล์ แล้วกด Commit changes

### B. เผยแพร่ด้วย Vercel
1. เข้า vercel.com ล็อกอินด้วยบัญชี GitHub
2. กด Add New → Project เลือก repository `grade-training` กด Import
3. หน้า Configure: Framework Preset เลือก **Other** ช่อง Build Command และ Output Directory **ปล่อยว่าง** แล้วกด Deploy
4. รอสถานะ Ready แล้วกด Visit จะได้ลิงก์สำหรับใช้ในวันอบรม

### แก้ไขหรืออัปเดตภายหลัง
อัปโหลดไฟล์ที่แก้ไปวางทับใน GitHub (Add file → Upload files) แล้ว Commit ชื่อไฟล์ต้องตรงเดิม Vercel จะอัปเดตเว็บให้เอง เสร็จแล้วรีเฟรชแรง ๆ (Ctrl+Shift+R)

## วิธีใช้ตอนบรรยาย
- ลูกศรซ้าย/ขวา, Space, PageUp/PageDown เปลี่ยนหน้า
- F เต็มจอ · N เปิด/ปิดโน้ตผู้บรรยาย
- แตะหรือคลิกครึ่งขวาของจอ = หน้าถัดไป ครึ่งซ้าย = ย้อนกลับ ปัดซ้าย-ขวาบนมือถือและ iPad ได้
- ปุ่ม "PDF" ที่แถบด้านล่าง เปิดหน้าพิมพ์ เลือก "บันทึกเป็น PDF" ได้ไฟล์ 24 หน้า
- ลิงก์ตรงไปหน้าใดหน้าหนึ่ง เช่น `ลิงก์ของคุณ/#12`

## หมายเหตุ
ฟอนต์ (Prompt, Noto Sans Thai) โหลดจาก Google Fonts ต้องมีอินเทอร์เน็ตตอนเปิดครั้งแรก
ภาพหน้าจอในสไลด์อยู่ในโฟลเดอร์ `images` เปลี่ยนภาพได้โดยใช้ชื่อไฟล์เดิม
