# แนวทางการทำงาน ESP32 blink cook book
## 1. ระบุตัวอย่างที่ใช้ ว่าเอามาจากตัวอย่างไหน
- เลือกโปรเจค blink จาก show examples แล้วกด create
![image](https://github.com/user-attachments/assets/87fdda27-44d8-4216-a478-a8f8a539230b)
## 2. ระบุว่า จะแก้ไขตรงไหนบ้าง เพื่ออะไร 
- โค้ดดีงกล่าวเป็นการทำให้ LED กระพริบ โดยใช้ไดรเวอร์ GPIO ซึ่งไม่ต้องแก้ไขไฟล์ blink_example_main.c และ สามารถไปที่ Example Configuration เพื่อตั้งค่าส่วนต่างๆได้
![image](https://github.com/user-attachments/assets/027d6800-7cb1-4567-8f52-0524eb4fb480)

## 3. แสดงขั้นตอนการทำ project
- ลองกด build และไปที่ Example Configuration สามารถตั้งค่า ขา GPIO และระยะเวลาติด-ดับได้
![image](https://github.com/user-attachments/assets/bd04e6eb-dd56-45b6-8dc0-17a1794798f9)
## 4. แสดงผลการทำ project
- ไฟจะกระพริบทุกๆ 1 วิตามที่ตั้งค่าเอาไว้ และแสดงผลที่ terminal

## 5. สรุปผลการทำ project 
โปรเจคนี้ทำเกี่ยวกับ LED กระพริบซึ่งสามารถตั้งค่า GPIO/ประเภทของ LED ได้ ในเมนู Example Configuration
