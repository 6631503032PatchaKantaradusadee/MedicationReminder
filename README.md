**ชื่อ - นามสกุล (Full Name):** Patcha Kantaradusadee

**รหัสนักศึกษา (Student ID):**  6631503032

**ชื่อแอป (App Name):**  

**Framework ที่ใช้ (Framework Used):** React Native

**ลิงก์ GitHub Repository:** https://github.com/6631503032PatchaKantaradusadee/MedicationReminder

**ลิงก์ไฟล์ติดตั้ง (APK/IPA):** https://expo.dev/accounts/thanaruktk/projects/MedicationReminder/builds/079afcc9-a1ed-4c7c-98c0-5b3ef58e89ea

---

## 1. การออกแบบแอป | App Concept and Design (2 คะแนน / 2 pts)

### 1.1 ผู้ใช้งานเป้าหมาย | User Personas  
```markdown
Persona 1:  
- ชื่อ: จอร์จ
- อายุ: 20 ปี  
- อาชีพ: นักศึกษาปี 2  
- ความต้องการ: ช่วยเตือนให้กินยาให้ตรงเวลา

Persona 2:  
- ชื่อ: บีม
- อายุ: 22 ปี  
- อาชีพ: นักศึกษาฝึกงาน  
- ความต้องการ: ควบคุมการกินยาและติดตามสุขภาพ

```

### 1.2 เป้าหมายของแอป | App Goals  
**ตัวอย่าง (Example):**
```markdown
- ช่วยให้ผู้ใช้งานไม่ลืมกินยา
- เพิ่มความปลอดภัยในการใช้ยา
- อำนวยความสะดวกแก่ผู้ดูแลผู้ป่วย
```

### 1.3 โครงร่างหน้าจอ / Mockup  
**ใส่รูปภาพ หรือคำอธิบายแต่ละหน้าหลัก 3 หน้า | Attach image or describe 3 main pages**
![Screenshot_20250430_090140_Expo_Go](https://github.com/user-attachments/assets/8e51199e-4785-4fcb-a5fd-5215102c22bc)
![Screenshot_20250430_090108_Expo_Go](https://github.com/user-attachments/assets/86e5f11d-2782-4a93-a11f-0d73af4c8cf9)
![Screenshot_20250430_090126_Expo_Go](https://github.com/user-attachments/assets/4093f070-009b-4db6-9472-75029cd39bcd)


### 1.4 การไหลของผู้ใช้งาน | User Flow  
**ตัวอย่าง (Example):**
```markdown
เปิดแอป > เข้าสู่ระบบ > สร้างโปรไฟล์ > ตั้งค่ายา > กลับหน้าหลัก > เข้าตั้งค่า > เปิดรับการแจ้งเตือน
```

---

## 2. การพัฒนาแอป | App Implementation (4 คะแนน / 4 pts)

### 2.1 รายละเอียดการพัฒนา | Development Details  
**เครื่องมือที่ใช้ / Tools used:**
```markdown
- React Native
- Expo
- Package: Provider, SharedPreferences, react-navigation, react-native-gesture-handler, react-native-modalize, react-native-reanimated, react-native-safe-area-context, react-native-screens, react-native-async-storage, react-native-picker-select, react-native-community/datetimepicker

```

### 2.2 ฟังก์ชันที่พัฒนา | Features Implemented  
**Checklist:**
```markdown
- [x] เพิ่มตัวยา
- [x] ลบตัวยา
- [x] ส่งการแจ้งเตือน
- [ ] แสดงรายละเอียดยา
```

### 2.3 ภาพหน้าจอแอป | App Screenshots  
**แนบภาพหรือ URL (Attach images or image links):**
![Screenshot_20250430_090140_Expo_Go](https://github.com/user-attachments/assets/c33f4240-7dde-41fd-9cdf-dedfe3219f01)
![Screenshot_20250430_090108_Expo_Go](https://github.com/user-attachments/assets/85650115-2c5b-4e83-9143-36902a1ee216)
![Screenshot_20250430_090126_Expo_Go](https://github.com/user-attachments/assets/341866cf-6c73-46ba-8e7b-daaa0a886ef9)


---

## 3. การ Build และติดตั้งแอป | Deployment (2 คะแนน / 2 pts)

### 3.1 ประเภท Build | Build Type
- [x] Debug  
- [ ] Release  

### 3.2 แพลตฟอร์มที่ทดสอบ | Platform Tested  
- [x] Android  
- [ ] iOS  

### 3.3 ไฟล์ README และวิธีติดตั้ง | README & Install Guide  
**แนบไฟล์หรือคำอธิบายการติดตั้งแอป | Insert steps**
```markdown
1. ดาวน์โหลดไฟล์ .apk
2. เปิดในอุปกรณ์ Android
3. ติดตั้งผ่าน File Manager
```

---

## 4. การสะท้อนผลลัพธ์ | Reflection (2 คะแนน / 2 pts)
```markdown
- พบปัญหาเวลาใช้ setState กับ async function ทำให้การอัปเดตสถานะไม่ทำงานตามที่คาดไว้ในบางกรณี
- แอปของเราค่อนข้างเน้นการบันทึกข้อมูลในระบบของตัวเอง
- อยากเพิ่มดูประวัติการกินยา
- หากมีเวลาระบบรางวัล และแรงจูงใจ
```

---

## 5. การใช้ AI ช่วยพัฒนา | AI Assisted Development (Bonus / ใช้ประกอบการพิจารณา)

### 5.1 ใช้ AI ช่วยคิดไอเดีย | Idea Generation
```markdown
Prompt ที่ใช้:  
"ช่วยคิดไอเดียแอปดูแลผู้ป่วยหรือเตือนให้กินยาอย่างมีประสิทธิภาพ"

ผลลัพธ์:  
ได้แนวคิดแอป Medication Reminder ที่มีฟีเจอร์แจ้งเตือน และบันตัวยา
```

### 5.2 ใช้ AI ช่วยออกแบบ UI | UI Layout Prompt
```markdown
Prompt ที่ใช้:  
"ช่วยออกแบบ layout สำหรับแอปเตือนกินยา โดยมีหน้า Home, Medtime, Timereminder และ Setting"

ผลลัพธ์:  
ได้หน้า layout ที่ชัดเจนและใช้งานง่าย และหน้าการทำงาน 3 หน้า
```

### 5.3 ใช้ AI ช่วยเขียนโค้ด | Code Writing Prompt
```markdown
Prompt ที่ใช้:  
"ช่วยเขียน React Native code สำหรับเพิ่มข้อมูลยาและแสดงรายการยาในหน้า Home"

ผลลัพธ์:  
ได้โค้ดที่ใช้ `useState` และ `FlatList` สำหรับเพิ่มและแสดงรายการยา พร้อม UI ที่เรียบง่ายใช้งานได้ทันที
```

### 5.4 ใช้ AI ช่วย debug | Debug Prompt
```markdown
Prompt ที่ใช้:  
"หน้า Add Medication กดปุ่ม Save แล้วแอปค้าง ช่วยหาสาเหตุ"

ผลลัพธ์:  
AI ตรวจพบว่าไม่ได้ใส่ `onPress` อย่างถูกต้อง และไม่มีการตรวจสอบ input ก่อนบันทึก → เสนอวิธีแก้ไขและเพิ่มการ validation
```

### 5.5 ใช้ AI ช่วย Deploy | Deployment Prompt
```markdown
Prompt ที่ใช้:  
"ช่วยบอกวิธีสร้างไฟล์ APK ใน React Native"

ผลลัพธ์:  
ได้คำสั่ง npm install -g eas-cli, eas login, eas build:configure, eas build -p android --profile preview พร้อมวิธีติดตั้ง
```

---
