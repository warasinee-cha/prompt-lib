# การเขียน Prompt อย่างมีประสิทธิภาพ

**ประมาณเวลาที่ใช้:** 60 นาที

ในแบบฝึกหัดนี้ คุณจะได้ฝึกเทคนิคการเขียน prompt ทั้ง 3 แบบที่เรียนในคลาส แต่ละบทเรียนมีตัวอย่างและแบบฝึกหัดที่จะช่วยให้คุณเชี่ยวชาญในการเขียน prompt อย่าลืมเก็บบันทึกการสนทนากับ AI ไว้ด้วยนะคะ เพราะจะต้องใช้ในการส่งงาน

## 1. การให้รายละเอียดที่ชัดเจน

AI จะทำงานได้ดีที่สุดเมื่อได้รับคำสั่งที่ละเอียดและชัดเจน มาฝึกการเขียน prompt ที่มีรายละเอียดกันค่ะ

### ตัวอย่าง prompt แบบง่าย vs. แบบละเอียด

ลองใช้ prompts เหล่านี้และสังเกตความแตกต่างของคำตอบ:

```prompt
ช่วยเขียนอีเมลถึงครูหน่อย
```

```prompt
ช่วยเขียนอีเมลถึงครูที่ปรึกษาชมรมคอมพิวเตอร์ โดยมีรายละเอียดดังนี้:
- ผมเป็นนักเรียน ม.5 สนใจด้านการเขียนโปรแกรมและ AI มาก
- เคยได้รางวัลชนะเลิศการแข่งขันเขียนโปรแกรมระดับเขต
- เคยผ่านการอบรม Python จาก สสวท.
- อยากสมัครเป็นประธานชมรมคอมพิวเตอร์ในปีการศึกษาหน้า
- ต้องการนำเสนอโครงการพัฒนาเว็บไซต์โรงเรียนใหม่
กรุณาเขียนให้สุภาพ เป็นทางการ และแสดงให้เห็นถึงวิสัยทัศน์ในการพัฒนาชมรม
```

```prompt
Help me write a letter to my teacher.
```

```prompt
Help me write a letter to my science teacher requesting an extension for my biology project. Details:
- I'm in 10th grade
- The project is about ecosystem conservation
- I need 3 more days because I'm waiting for data from my field research
- I have a good academic record and never asked for extensions before
- Tone should be polite and professional
```

### แบบฝึกหัดที่ 1:
เลือกทำ 1 ข้อจากตัวอย่างข้างล่าง หรือคิดหัวข้อใหม่ที่อยากฝึกเขียน prompt แบบละเอียดก็ได้ ลองเขียน prompt แบบง่ายก่อน แล้วปรับให้มีรายละเอียดมากขึ้น สังเกตว่าคำตอบของ AI เปลี่ยนไปอย่างไร:

```prompt
ช่วยเตรียมบทพูดสำหรับการนำเสนอโครงงานวิทยาศาสตร์เรื่องพลังงานแสงอาทิตย์
```

```prompt
Help me prepare for my presentation about renewable energy.
```

```prompt
แนะนำหัวข้อสำหรับเรียงความภาษาอังกฤษ
```

💡 **เคล็ดลับ**: ถ้าคิดไม่ออกว่าจะใส่รายละเอียดอะไรดีให้คิดถึงองค์ประกอบของ prompt ที่ดีได้แก่

- Context (บริบท) – งานของเราคืออะไร จะเอาคำตอบของ AI ไปทำอะไร ปัญหาของเราคืออะไร
- Input Data (ข้อมูลนำเข้า) – อะไรคือข้อมูลเบื้องต้นที่เราทราบและ AI ก็ควรทราบด้วย
- Instructions (คำสั่ง) – สิ่งที่เราอยากให้ AI ช่วยทำ
- Output Format (ลักษณะผลลัพธ์) – เราอยากได้ผลลัพธ์แบบไหน

## 2. การแนะนำวิธีคิดให้กับ AI

การแบ่งงานซับซ้อนเป็นขั้นตอนย่อยๆ จะช่วยให้ AI ตอบได้ดีขึ้น มาฝึกเขียน prompt แบบมีขั้นตอนกัน

### ตัวอย่างการคิดแบบเป็นขั้นตอน
ลองใช้ prompts เหล่านี้และสังเกตความแตกต่างของคำตอบ:

```prompt
ถ้าปล่อยวัตถุจากความสูง 20 เมตร จะใช้เวลาตกถึงพื้นกี่วินาที
```

```prompt
ช่วยวิเคราะห์โจทย์ฟิสิกส์เรื่องการตกอย่างอิสระนี้:
"วัตถุถูกปล่อยจากตึกสูง 20 เมตร จงหา:
1. เวลาที่วัตถุใช้ในการตกถึงพื้น
2. ความเร็วของวัตถุขณะกระทบพื้น
3. ความเร็วเฉลี่ยตลอดการเคลื่อนที่"

กรุณาแสดงวิธีทำตามขั้นตอนนี้:
1. เขียนสมการที่เกี่ยวข้องทั้งหมดพร้อมอธิบายความหมายของตัวแปร
2. วิเคราะห์ว่าต้องใช้สมการไหนหาอะไรบ้าง จัดลำดับการแก้สมการ
3. แสดงการแทนค่าและคำนวณทีละขั้น
4. ยกตัวอย่างการประยุกต์ใช้ความรู้นี้ในชีวิตจริงหรือในงานวิศวกรรม

แสดงหน่วยทุกขั้นตอน และอธิบายแนวคิดให้เข้าใจง่าย
```

### แบบฝึกหัดที่ 2:
เลือกทำ 1 ข้อจากตัวอย่างข้างล่างหรือคิดงานที่ต้องทำหลายขั้นตอนขึ้นมาเองก็ได้ ลองเขียน prompt ที่แบ่งงานเป็นขั้นตอนย่อยๆ ให้ AI เข้าใจและทำตามได้ง่าย:

```prompt
วางแผนการอ่านหนังสือสอบปลายภาค
```

```prompt
ช่วยวางแผนจัดกิจกรรมรณรงค์ลดขยะพลาสติกในโรงเรียน
```

```prompt
Design a social media campaign for the school festival.
```

## 3. การทดลองและปรับปรุง

มาฝึกการปรับปรุง prompt ให้ดีขึ้นเรื่อยๆ กัน นี่คือตัวอย่างการพัฒนา prompt ทีละขั้น:

```prompt
How do I improve my English?
```

```prompt
What are the best methods for a Thai high school student to improve English speaking and writing skills?
```

```prompt
I'm a Thai high school student preparing for international university applications. Please suggest:
- Daily English practice activities (30-60 mins per day)
- Recommended apps and online resources
- Speaking practice methods when I don't have foreign friends
- Writing exercise ideas focused on academic English
- Tips for expanding vocabulary through daily activities
```

### แบบฝึกหัดที่ 3:
เลือกทำ 1 ข้อจากตัวอย่าง หรือคิดคำถามที่อยากถาม AI ขึ้นมาเองก็ได้ ลองเขียน prompt 3 รอบ โดยแต่ละรอบให้เพิ่มรายละเอียดและปรับปรุงจากผลลัพธ์ที่ได้ในรอบก่อน:

```prompt
ช่วยแนะนำงานอดิเรกให้หน่อย
```

```prompt
แนะนำหนังสือที่น่าอ่าน
```

```prompt
Help me create a study schedule.
```

💡 **เคล็ดลับ**: หลังได้คำตอบแต่ละครั้ง ลองถามตัวเองว่า

- มีข้อมูลสำคัญอะไรที่ยังขาดไป
- AI เข้าใจผิดหรือคาดเดาอะไรไปเองบ้าง
- ควรเพิ่มบริบทหรือรายละเอียดอะไรอีก


