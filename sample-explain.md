# sample-explain
## การทดลองที่ 1 เรื่อง การเขียนโปรแกรมเพื่อรันบนไมโครคอนโทรเลอร์

เสียบ microcontroller ESP01 เข้าที่USBที่ใช้ในการเชื่อม computer จิ๋ว upload program แล้วrun code ผลลัพธ์คือ นับตั้งแต่ 1 ไปเรื่่อยๆ

## การทดลองที่ 2 เรื่อง การเขียนโปรแกรมค้นหาไวไฟ

เสียบ microcontroller ESP01 เข้าที่USBที่ใช้ในการเชื่อม computer จิ๋ว upload program wifi แล้วrun program ผลลัพธ์ คือ scan wifi ที่สามารถรับสัญญาณได้

## การทดลองที่ 3 เรื่อง การเขียนโปรแกรมเอ้าพุทสัญญาณดิจิทัล

ต่อ microcontroller ESP01 กับadapterและเสียบเข้าที่USBที่ใช้ในการเชื่อม computer จิ๋ว ต่อadapterกับportและต่อเข้าที่หลอดLED upload program outputสู่ภายนอก run program ผลัพธ์ คือ LED ที่ต่อกับport 0 มีแสงสลับ on off ส่วนport 2 ไม่ได้ต่อ LEDจึงไม่มีแสง

## Run relay

microcontroller ESP01 ที่เขียนโปรแกรมในexample 3 มาต่อกับrelayและนำไปต่อกับแหล่งจ่ายไฟ เช่น พาวเวอร์แบงค์ เมื่อต่อจะได้ยินเสียงการทำงานและแสงไฟสลับ on off

## การทดลองที่ 4 เรื่อง การเขียนโปรแกรมอินพุทสัญญาณดิจิทัล

set port 0 เป็นinput port 2 เป็นoutput upload program input นำสายสีขาวที่เป็น port 0 จิ้มไปที่ 0 LED สว่างโดยโปรแกรมจะอ่านค่า read 0 แต่ถ้าไม่ได้จิ้มจะอ่านค่า read 1 นำsensor มาต่อจะเห็นว่าเมื่อเอามือบังแสง LED จะดับโปรแกรมอ่านค่า read 1 แต่ถ้าเอามือออกจะอ่านค่า read 0 ไฟสว่าง

## การทดลองที่ 5 เรื่อง การเขียนโปรแกรมเชื่อมต่อไวไฟและเว็บเซอร์เวอร์

upload program สร้างwebserverผ่านwifi เสียบ microcontroller ESP01 ทดสอบโดยเปิด web browser

## การทดลองที่ 6 เรื่อง การเขียนโปรแกรมสร้างไวไฟแอคเซสพอยต์ (Wifi AP)

upload program สร้างwifiขึ้นมาเอง ทดสอบโดยการใช้โทรศัพท์ค้นหาwifi
