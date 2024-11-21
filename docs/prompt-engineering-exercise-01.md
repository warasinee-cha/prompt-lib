# Prompt Engineering Fundamentals

In this exercise, you'll practice the three key techniques for effective prompt writing we covered in class. Each lesson includes examples and hands-on practice to help you master these skills. Remember to save your chat logs - you'll need them for the mini project!

## Lesson 1: Being Detailed and Specific

AI assistants work best when given clear, detailed instructions. Let's practice making our prompts more specific.

### Basic vs. Detailed Prompts

Try these prompts and observe the difference in responses:

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

### แบบฝึกหัดที่ 1:
เลือกทำ 1 ข้อจากตัวอย่างข้างบน หรือคิดหัวข้อใหม่ที่อยากฝึกเขียน prompt แบบละเอียดก็ได้ ลองเขียน prompt แบบง่ายก่อน แล้วปรับให้มีรายละเอียดมากขึ้น สังเกตว่าคำตอบของ AI เปลี่ยนไปอย่างไร:

```prompt
Help me prepare for my presentation about renewable energy.
```

```prompt
ช่วยเตรียมบทพูดสำหรับการนำเสนอโครงงานวิทยาศาสตร์เรื่องพลังงานแสงอาทิตย์
```

```prompt
Give me ideas for my creative writing assignment.
```

💡 **Tip**: Think about the 5W1H (Who, What, When, Where, Why, How) when adding details to your prompts.

## Lesson 2: Guiding the Model's Thinking Process

Breaking down complex tasks into steps helps AI provide better responses. Let's practice creating structured prompts.

### Example of Step-by-Step Thinking

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
1. เขียนสมการการที่เกี่ยวข้องทั้งหมดพร้อมอธิบายความหมายของตัวแปร
2. วิเคราะห์ว่าต้องใช้สมการไหนหาอะไรบ้าง จัดลำดับการแก้สมการ
3. แสดงการแทนค่าและคำนวณทีละขั้น
4. ยกตัวอย่างการประยุกต์ใช้ความรู้นี้ในชีวิตจริงหรือในงานวิศวกรรม

แสดงหน่วยทุกขั้นตอน และอธิบายแนวคิดให้เข้าใจง่าย
```

### Practice Exercise 2:
Create step-by-step prompts for these tasks:

```prompt
วางแผนการอ่านหนังสือสอบปลายภาค
```

```prompt
Design a social media campaign for the school festival.
```

```prompt
ช่วยวางแผนจัดกิจกรรมรณรงค์ลดขยะพลาสติกในโรงเรียน
```

## Lesson 3: Experimenting and Iterating

Let's practice improving prompts through iteration. Here's an example series:

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

### Practice Exercise 3:
Improve these prompts through 3 iterations:

```prompt
ช่วยสอนวิธีพับกระดาษโอริกามิ
```

```prompt
Help me create a study schedule.
```

```prompt
แนะนำหนังสือที่น่าอ่าน
```

💡 **Tip**: After each response, ask yourself:
- What's missing from the output?
- What assumptions did the AI make?
- What additional context would help?

