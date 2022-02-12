# sample-explain
## การทดลองที่ 1 เรื่อง การเขียนโปรแกรมเพื่อรันบนไมโครคอนโทรเลอร์
![image](https://user-images.githubusercontent.com/98943460/153704612-15337426-9eb5-425d-88e4-ee6db581bf10.png)

เสียบ microcontroller ESP01 เข้าที่USBที่ใช้ในการเชื่อม computer จิ๋ว upload program แล้วrun code ผลลัพธ์คือ นับตั้งแต่ 1 ไปเรื่่อยๆ
## การทดลองที่ 2 เรื่อง การเขียนโปรแกรมค้นหาไวไฟ

![image](https://user-images.githubusercontent.com/98943460/153704570-cb105dc8-c36f-43db-893e-de23a2f0af5a.png)

เสียบ microcontroller ESP01 เข้าที่USBที่ใช้ในการเชื่อม computer จิ๋ว upload program wifi แล้วrun program ผลลัพธ์ คือ scan wifi ที่สามารถรับสัญญาณได้

## การทดลองที่ 3 เรื่อง การเขียนโปรแกรมเอ้าพุทสัญญาณดิจิทัล
![image](https://user-images.githubusercontent.com/98943460/153704661-5618b94e-801f-491c-b7ae-ef429475dea4.png)

เสียบ microcontroller ESP01 เข้าที่USBที่ใช้ในการเชื่อม computer จิ๋ว upload program wifi แล้วrun program ผลลัพธ์ คือ scan wifi ที่สามารถรับสัญญาณได้
เมื่อต่อกับrelayและนำไปต่อกับแหล่งจ่ายไฟ เช่น พาวเวอร์แบงค์ เมื่อต่อจะได้ยินเสียงการทำงานและแสงไฟสลับ on off

## การทดลองที่ 4 เรื่อง การเขียนโปรแกรมอินพุทสัญญาณดิจิทัล

![image](https://user-images.githubusercontent.com/98943460/153704722-7e9c443e-c303-4dbe-bd64-6c246efc0975.png)

set port 0 เป็นinput port 2 เป็นoutput upload program input นำสายสีขาวที่เป็น port 0 จิ้มไปที่ 0 LED สว่างโดยโปรแกรมจะอ่านค่า read 0 แต่ถ้าไม่ได้จิ้มจะอ่านค่า read 1 นำsensor มาต่อจะเห็นว่าเมื่อเอามือบังแสง LED จะดับโปรแกรมอ่านค่า read 1 แต่ถ้าเอามือออกจะอ่านค่า read 0 ไฟสว่าง

## การทดลองที่ 5 เรื่อง การเขียนโปรแกรมเชื่อมต่อไวไฟและเว็บเซอร์เวอร์

![image](https://user-images.githubusercontent.com/98943460/153704773-dd382718-8488-4ca8-ad30-bc063a3d3515.png)

upload program สร้างwebserverผ่านwifi เสียบ microcontroller ESP01 ทดสอบโดยเปิด web browser

## การทดลองที่ 6 เรื่อง การเขียนโปรแกรมสร้างไวไฟแอคเซสพอยต์ (Wifi AP)

![image](https://user-images.githubusercontent.com/98943460/153704873-2a680be9-0b61-475b-9e4c-cb4b7459a733.png)

upload program สร้างwebserverผ่านwifi เสียบ microcontroller ESP01 ทดสอบโดยเปิด web browser
