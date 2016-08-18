# การใช้งานบริการระบบคลาวด์ด้วย Thingspeak

Thingspeak เป็น Platform as a Services ที่ให้บริการเพื่อเก็บข้อมูลแบบเรียลไทม์ \(Real-time\) โดยข้อมูลที่ส่งขึ้นไปจะแสดงข้อมูลในรูปแบบกราฟ สามารถอัดเดทข้อมูล หรือเรียกดูจากที่ใดก็ได้ ซึ่งก็คล้าย ๆ กับ netpie.io แต่สิ่งที่ต่างกัน คือ Thingspeak จะแสดงผลข้อมูลในรูปแบบกราฟ และสามารถนำกราฟที่แสดงผลไปใช้งานที่เว็บได้อีกด้วย \(iframe\) ซึ่งข้อมูลที่ดึงไปแสดงผลบนเว็บ ก็จะสามารถอัพเดทข้อมูลแบบเรียลไทม์ \(Real-time\)

**ขั้นตอนการใช้งาน Thingspeak**

1. [ทำการสมัคร และเข้าสู่ระบบเพื่อใช้งาน Thingspeak ](https://thingspeak.com)
  ![](/images/thingspeak1.jpg)
2. เลือก Channels --&gt; My Channels
  ![](/images/thingspeak2.jpg)
3. ทำการสร้าง Channels ใหม่ขึ้นมาโดยเลือกที่ New Channels

  ![](/images/thingspeak3.jpg)

4. กรอก Name เพื่อตั้งชื่อแชลแนล และ Field \(ในตัวอย่างจะตั้ง Field1 ชื่อ Temp และ Field2 ชื่อ humid เพื่อใช้สำหรับรับข้อมูลอุณหภูมิ และความชื้นในอากาศ\)

  ![](/images/thingspeak4.jpg)

5. จะได้ Channel ID นั่นหมายความว่าสร้างแชลแนลสำหรับเก็บข้อมูลเรียบร้อยแล้ว
  ![](/images/thingspeak5.jpg)
6. เมื่อทำการตั้งค่าแชลแนลเสร็จ ให้คลิ๊กที่หัวข้อ API Keys จะได้ key เพื่อส่งข้อมูลมายังแชลแนลนี้

  ![](/images/thingspeak6.jpg)
7. ทดลองส่งค่าขึ้นมายัง Field ต่าง ๆ thingspeak จะทำการ plot ข้อมูลที่ส่งขึ้นมาเป็นกราฟให้ \([ตัวอย่างโค้ด](https://github.com/bavensky/ESPlite_Thingspeak "ตัวอย่างโค้ด")\)

  ![](/images/thingspeak7.jpg)
8. โดยสามารถแก้ไข หรือตั้งค่าต่าง ๆ โดยคลิกที่ Chart Options เพียงเท่านี้ก็สามารถใช้งาน Thingspeak ได้แล้ว

  ![](/images/thingspeak8.jpg)

