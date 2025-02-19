## ตัวอย่าง Prompt ง่ายๆ ทดลองคุยก่อน

```
ช่วยอธิบายเรื่องการแบ่งเซลล์แบบ Mitosis ให้เข้าใจง่ายๆ เหมือนเล่านิทาน
```

```
แต่งคำคล้องจองสั้นๆ เกี่ยวกับการรักษาสิ่งแวดล้อม สำหรับการนำเสนอหน้าชั้น
```

```
ฉันอายุ 17 แล้ว จะต้องเลือกคณะที่จะเรียนแต่ยังไม่รู้จะเลือกอันไหน เริ่มไงดี?
```

```
มีเทคนิคอะไรบ้างที่จะช่วยให้นำเสนองานหน้าห้องแล้วไม่ตื่นเต้น?
```

## เทคนิค Prompt Engineering ขั้นพื้นฐาน

### เทคนิคที่ 1 : ให้คำสั่งที่ละเอียดและชัดเจน

AI เหมือนเด็กจบใหม่ที่ต้องการข้อมูลพื้นฐานให้ครบถ้วนเพื่อทำงานได้ดี หากให้ข้อมูลไม่พอ AI จะไม่สามารถสร้างเนื้อหาที่ตรงกับความต้องการของเราได้

**ตัวอย่าง prompt ที่ไม่มีรายละเอียด**

```
ช่วยเขียนอีเมลถึงอาจารย์ขอเข้าร่วมแล็บหุ่นยนต์
```

**ตัวอย่าง prompt ที่มีรายละเอียด**

```
ช่วยเขียนอีเมลถึงอาจารย์ขอเข้าร่วมแล็บหุ่นยนต์ โดยมีรายละเอียดดังนี้
- ผมเป็นนักเรียนชั้น ม.5 สนใจด้านหุ่นยนต์และ AI มาก
- เคยได้รางวัลชนะเลิศการแข่งขันหุ่นยนต์ระดับเขต
- เคยเข้าค่าย สสวท. ด้านหุ่นยนต์
- อยากได้ประสบการณ์ทำงานในแล็บจริงๆ ในช่วงปิดเทอม
- ยินดีทำงานโดยไม่มีค่าตอบแทน เพื่อเรียนรู้และสั่งสมประสบการณ์ 

กรุณาเขียนให้สุภาพ เป็นทางการ และแสดงให้เห็นถึงความกระตือรือร้นในการเรียนรู้
```

### เทคนิคที่ 2 : แนะนำวิธีคิดให้กับบอท

เมื่อเราต้องการให้ AI ทำงานที่ซับซ้อน การแบ่งงานเป็นขั้นตอนย่อยๆ จะช่วยให้ผลลัพธ์ออกมาเป็นระบบและมีคุณภาพมากขึ้น

**ตัวอย่าง prompt ที่ไม่มีวิธีคิด**

```
คิดชื่อเล่นแมว 10 ชื่อ
```

**ตัวอย่าง prompt ที่มีวิธีคิด**

```
ช่วยคิดชื่อเล่นแมว 10 ชื่อโดยทำตามขั้นตอนนี้:
- หาคำที่แปลว่าแมว จากภาษาต่างๆ ทั่วโลก
- หาคำไทยที่พ้องเสียงกับคำเหล่านั้น
- แปลงคำไทยนั้นให้ฟังดูน่ารัก
```

### เทคนิคที่ 3 : ทดลองและปรับปรุง

การเขียน Prompt ที่ดีเกิดจากการลองผิดลองถูก ไม่ต้องกลัวว่า Prompt แรกจะไม่สมบูรณ์ ให้เริ่มต้นง่ายๆ แล้วค่อยๆ ปรับปรุง

**รอบที่ 1**

```
ช่วยสรุปเรื่องการสังเคราะห์แสง
```

**รอบที่ 2**

```
ช่วยสรุปกระบวนการสังเคราะห์แสงให้เข้าใจง่าย สำหรับนักเรียน ม.4
```

**รอบที่ 3**

```
สรุปกระบวนการทางชีววิทยาและเคมีในการสังเคราะห์แสง
- ใช้ภาษาที่เข้าใจง่ายแต่มีรายละเอียดศัพท์ชีววิทยา วงเล็บอธิบายศัพท์ที่เข้าใจยากสำหรับเด็กม.ปลาย
- อธิบายกระบวนการไม่เกิน 5 ข้อ
- ยกตัวอย่างให้เห็นภาพ เปรียบเทียบกับสิ่งที่เห็นในชีวิตประจำวัน
- ให้เทคนิคช่วยจำด้วย
```