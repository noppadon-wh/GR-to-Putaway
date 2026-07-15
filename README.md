# GR-to-Putaway

ระบบจัดการสินค้ารับเข้า (Goods Receipt) ไปยังจุดเก็บสินค้า (Putaway) โดยอัตโนมัติ

## 📋 คำอธิบายโปรเจค

GR-to-Putaway เป็นระบบที่ออกแบบมาเพื่อจัดการกระบวนการรับสินค้าและการจัดเก็บสินค้าในคลังสินค้า (Warehouse) ให้เป็นไปอย่างมีประสิทธิภาพและลดข้อผิดพลาด

## ✨ ฟีเจอร์หลัก

- ✅ สร้างและจัดการใบรับสินค้า (GR)
- ✅ ระบบเก็บสินค้าอัตโนมัติ (Putaway)
- ✅ ติดตามสถานะสินค้าแบบ Real-time
- ✅ รายงานสินค้ารับเข้า
- ✅ จัดการต้องห้ามและข้อผิดพลาด

## 🛠 เทคโนโลยีที่ใช้

- **Backend**: [ระบุเทคโนโลยี]
- **Frontend**: [ระบุเทคโนโลยี]
- **Database**: [ระบุเทคโนโลยี]
- **Framework**: [ระบุเทคโนโลยี]

## 📦 การติดตั้ง

### ข้อกำหนด
- Node.js v14+
- npm หรือ yarn

### ขั้นตอนการติดตั้ง

1. Clone repository
```bash
git clone https://github.com/noppadon-wh/GR-to-Putaway.git
cd GR-to-Putaway
```

2. ติดตั้ง dependencies
```bash
npm install
```

3. ตั้งค่า environment variables
```bash
cp .env.example .env
# แก้ไข .env ตามความต้องการของคุณ
```

4. รัน application
```bash
npm start
```

## 🚀 วิธีการใช้งาน

### ตัวอย่างการใช้งาน

```bash
# เริ่มต้น server
npm run dev

# Run tests
npm test

# Build production
npm run build
```

## 📚 API Documentation

### สร้างใบรับสินค้า
```
POST /api/gr
Body: {
  "reference": "GR-001",
  "items": [...]
}
```

### เรียกดู Putaway
```
GET /api/putaway/:id
```

[ดูเอกสาร API เพิ่มเติม](./docs/API.md)

## 🧪 การทดสอบ

```bash
npm test
npm run test:coverage
```

## 📝 ไฟล์ที่สำคัญ

- `package.json` - ข้อมูล project และ dependencies
- `src/` - โค้ด source
- `tests/` - Test cases
- `docs/` - Documentation

## 🐛 การรายงาน Issues

พบปัญหาหรือข้อเสนอแนะ? โปรดสร้าง [Issue](https://github.com/noppadon-wh/GR-to-Putaway/issues) ใหม่

## 🤝 การสนับสนุน

หากต้องการมีส่วนร่วมในโปรเจค:

1. Fork repository
2. สร้าง branch สำหรับฟีเจอร์ (`git checkout -b feature/AmazingFeature`)
3. Commit การเปลี่ยนแปลง (`git commit -m 'Add some AmazingFeature'`)
4. Push ไปที่ branch (`git push origin feature/AmazingFeature`)
5. เปิด Pull Request

## 📄 License

โปรเจคนี้มี License - ดู [LICENSE](./LICENSE) ไฟล์สำหรับรายละเอียด

## 👤 ผู้พัฒนา

**Noppadon WH**
- GitHub: [@noppadon-wh](https://github.com/noppadon-wh)

## 📞 ติดต่อ

หากมีคำถามหรือข้อเสนอแนะ สามารถติดต่อได้ที่:
- Email: [ระบุอีเมล]
- Issues: [GitHub Issues](https://github.com/noppadon-wh/GR-to-Putaway/issues)

---

**หมายเหตุ**: โปรแกรมนี้ยังอยู่ในช่วงพัฒนา (Under Development) ซึ่งอาจมีการเปลี่ยนแปลงและปรับปรุง
