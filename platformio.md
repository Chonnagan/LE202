# ติดตั้งโปรแกรมสำหรับไอโอที
## 1) Downloadโปรแกรมที่จำเป็น 
โหลด git python และ nodejs ตามลิ้งข้างล้างนี้

https://git-scm.com/download/win

https://www.python.org/downloads/windows/

https://nodejs.org/en/download/

จากนั้นติดตั้งทั้ง 3 โปรแกรม

## 2) Downloadโปรแกรมด้วย git
เปิด Command Prompt แล้วรันตามข้างล่างนี้

      
      git clone https://github.com/choompol-boonmee/iotset1.git
      

## 3) Downloadและติดตั้ง platformio
เปิด command prompt หรือ cmd เข้าไปโฟลเดอร์ iotset1

จากนั้นรันคำสั่ง


     pip install -U platformio
     

## 4) ทดสอบ
ตรวจสอบดูโฟลเดอร์ตัวอย่าง ex01,ex02,ex03

รันตัวอย่างที่ 1

cd iotset1/examples/ex01

pio run

จากนั้นก็ทำตัวอย่างที่ 2 และ 3 เหมือนกัน
