# Tutorial-9-Embedded-Systems-and-IoT
การใช้งาน RFID (Radio Frequency Identification)


Objectives
1. เขียนโปรแกรมเพื่ออ่านบัตรจาก RFID tag ได้

Hardware
1.	ESP32                 1	        
2.	RFID module (RC522)		1
3.  LED                   1
4.	Breadboard            1
5.	Computer	            1
6.	microUSB	            1 

Software
1. Arduino IDE v
--------------------
Instruction

1. ต่อสาย ESP32 กับ โมดูล RFID RC522 ดังนี้
  - SDA > GPIO21
  - SCK > SCK
  - MOSI > MOSI
  - MISO > MISO
  - GND > GND
  - RST > GPIO 00
  - 3v3 > 3v3
2. ติดตั้ง library ของ RFID module โดยพิมพ์คำว่า MFRC522 ในช่องค้นหา library แล้วเลือกติดตั้ง "MFRC522 by GithubCommunity" เวอร์ชัน 1.4.10
3. ดาวน์โหลดโค้ดจากไฟล์ lab9.ino
4. อัพโหลดโค้ดและทดสอบโดยการนำ tag ไปสแกนและดูหมายเลขของ tag ผ่าน serial monitor
5. เขียนเงื่อนไข หากสแกนด้วยบัตรสี่เหลี่ยม ให้ LED ติดสว่าง แต่หากสแกนด้วย tag สีฟ้า หลอด LED จะไม่ติด(ดับ)



