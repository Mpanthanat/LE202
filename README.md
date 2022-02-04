# LE202
# สรุปเนื้อหา 
## การเขียนrepo
  - #ใช้ในการกำหนดหัวข้อเรื่อง 
  - **or__ __ใช้ในการทำตัวหนา เช่น **le202**
  - *or_ _ ใช้ในการทำตัวเอียง เช่น *le202*
  - ~~ ~~ ใช้ในการขีดค่า เช่น ~~le202~~
  - **_ _ร่วมกันได้
  - *** ใช้เป็นตัวหนาและเอียง เช่น ***le202***
  - >ใช้อ้างอิงข้อความ เช่น le202 
  - ctrl+k ใส่url [ชื่อurl](url) 
  - ![ชื่อรูป](urlรูป) 
  
## Microcontroller
- digital
  การนำสัญญาณไฟฟ้าแทนด้วยตัวเลขหรือเรียกว่าดิจิตอล เป็นตัวเลขฐาน2 คือ 0 และ 1 ,มาใช้แทนตัวอักษรหรือตัวเลข  
 - voltag มี 2 ประเภท คือ กระแสสลับ และ กระแสตรง เช่น แบตเตอรี่ ไฟฟ้าจากอุปกรณ์USB
 - computer computerตัวแรกมีขนาดใหญ่เท่าตึกแล้วค่อยๆพัฒนาให้เหมาะสมกับการใช้างาน
 - internet ใช้เชื่อมโยงอุปกรณ์อิเล็กทรอนิกส์ต่างๆ
 - program log ภาษาในคอมพิวเตอร์มีการพัฒนามาอย่างต่อเนื่องเพื่อให้สามารถใช้เขียนโปรแกรมได้อย่างสะดวกและง่ายมากขึ้น
 - platformio เป็นการพัฒนา software แบบใหม่ที่ใช้วิธีเขียนโปรแกรมแบบเดียวแต่เขียนmicrocontrollerได้หลายแบบ
 
 ## ตัวอย่างการทดลอง
 - run example 1
    - เสียบ microcontroller ESP01 เข้าที่USBที่ใช้ในการเชื่อม computer จิ๋ว upload program แล้วrun code ผลลัพธ์คือ นับตั้งแต่ 1 ไปเรื่่อยๆ
 - run example 2
    - เสียบ microcontroller ESP01 เข้าที่USBที่ใช้ในการเชื่อม computer จิ๋ว upload program wifi แล้วrun program ผลลัพธ์ คือ scan wifi ที่สามารถรับสัญญาณได้
 - run example 3 
    - ต่อ microcontroller ESP01 กับadapterและเสียบเข้าที่USBที่ใช้ในการเชื่อม computer จิ๋ว  ต่อadapterกับportและต่อเข้าที่หลอดLED upload program outputสู่ภายนอก run program ผลัพธ์ คือ LED ที่ต่อกับport  0 มีแสงสลับ on off ส่วนport 2 ไม่ได้ต่อ LEDจึงไม่มีแสง
 - run relay
    - microcontroller ESP01 ที่เขียนโปรแกรมในexample 3 มาต่อกับrelayและนำไปต่อกับแหล่งจ่ายไฟ เช่น พาวเวอร์แบงค์
    เมื่อต่อจะได้ยินเสียงการทำงานและแสงไฟสลับ on off
 - run example 4
    - set port 0 เป็นinput prot 2 เป็นoutput upload program input นำสายสีขาวที่เป็น port 0 จิ้มไปที่ 0 LED สว่างโดยโปรแกรมจะอ่านค่า read 0 แต่ถ้าไม่ได้จิ้มจะอ่านค่า read 1 นำsensor มาต่อจะเห็นว่าเมื่อเอามือบังแสง LED จะดับโปรแกรมอ่านค่า read 1 แต่ถ้าเอามือออกจะอ่านค่า read 0 ไฟสว่าง
 - run wifi
    - upload program สร้างwebserverผ่านwifi เสียบ microcontroller ESP01 ทดสอบโดยเปิด web browser
 - run wiri AP
    - upload program สร้างwifiขึ้นมาเอง ทเสอบโดยการใช้โทรศัพท์ค้นหาwifi
