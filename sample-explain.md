# sample-explain
## การทดลองที่ 1 เรื่อง การเขียนโปรแกรมเพื่อรันบนไมโครคอนโทรเลอร์
![image](https://user-images.githubusercontent.com/98943460/153704612-15337426-9eb5-425d-88e4-ee6db581bf10.png)
1. set up setความเร็วอยู่ที่ 115200
2. loop เริ่มนับเพิ่มทีละ 1 
3. ให้ s เก็บค่าจากการคำนวณcnt
4. ให้ d เก็บค่าจากการคำนวณdelay

## การทดลองที่ 2 เรื่อง การเขียนโปรแกรมค้นหาไวไฟ

![image](https://user-images.githubusercontent.com/98943460/153704570-cb105dc8-c36f-43db-893e-de23a2f0af5a.png)
1. set up setความเร็วอยู่ที่ 115200
2. setup ตั้งค่าเกี่ยวกับwifi
3. loop แสกนหาwifi ถ้าไม่เจอให้แสดงผล not found แต่ถ้าเจอให้แสดงผลwifiที่เจอ


## การทดลองที่ 3 เรื่อง การเขียนโปรแกรมเอ้าพุทสัญญาณดิจิทัล
![image](https://user-images.githubusercontent.com/98943460/153704661-5618b94e-801f-491c-b7ae-ef429475dea4.png)
1. set up setความเร็วอยู่ที่ 115200
2. set up ให้port 0 เป็นoutput
3. loop ถ้าเป็นเลขคู่ให้แแสดงผล on ส่งค่า high ไปที่port 0 
4. ถ้าเป็นเลขคี่ให้แสดงผล off ส่งค่า low ไปที่ port 0

## การทดลองที่ 4 เรื่อง การเขียนโปรแกรมอินพุทสัญญาณดิจิทัล

![image](https://user-images.githubusercontent.com/98943460/153704722-7e9c443e-c303-4dbe-bd64-6c246efc0975.png)
1. set up setความเร็วอยู่ที่ 115200
2. setup ให้port 0 เป็น input และให้ port 2 เป็น output
3. loop ให้ตัวแปร val ใช้อ่านค่าดิจิทัล
4. ถ้า val อ่านค่า 1 ให้ส่ง low ไปที่ port 2
5. ถ้า val อ่านค่า 0 ให้ส่ง high ไปที่ port 2

## การทดลองที่ 5 เรื่อง การเขียนโปรแกรมเชื่อมต่อไวไฟและเว็บเซอร์เวอร์

![image](https://user-images.githubusercontent.com/98943460/153704773-dd382718-8488-4ca8-ad30-bc063a3d3515.png)
1. กำหนดชื่อ wifi และรหัสผ่าน และเปิดwebserver ที่ port 80
2. set up setความเร็วอยู่ที่ 115200
3. setup เชื่อมต่อwifi และแสดงผลwifi
4. ถ้าไม่พบให้แสดงผล not found 
5. ถ้าพบให้เริ่มต้นใช้งานserver โดยใช้ loop

## การทดลองที่ 6 เรื่อง การเขียนโปรแกรมสร้างไวไฟแอคเซสพอยต์ (Wifi AP)

![image](https://user-images.githubusercontent.com/98943460/153704873-2a680be9-0b61-475b-9e4c-cb4b7459a733.png)
1. ตั้งชื่อเครือข่าย wifi และ รหัสผ่าน 
2. กำหนด local IP และ gateway IP และ subnet IP
3. เปิดwebserver ที่ port 80
4. set up setความเร็วอยู่ที่ 115200
5. setup ตั้งค่าaccess point
6. เมื่อไม่พบให้เเสดงผล not found
7. ถ้าพบให้เริ่มต้นใช้งาน โดยวนloop
