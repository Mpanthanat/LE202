## Processor
    Processor คือ หน่วยประมวลผลกลางหรือ CPU เป็นฮาร์ดแวร์ชิ้นหนึ่งที่ทำให้คอมพิวเตอร์มีปฏิสัมพันธ์กับแอปพลิเคชันและโปรแกรมต่างๆที่ติดตั้งไว้ 
    CPU จะตีความคำสั่งของโปรแกรมและสร้างผลลัพธ์ตามที่คุณทำใช้งานอินเทอร์เฟซในขณะที่ใช้คอมพิวเตอร์
    หน้าที่ของ Processor
      1. อ่านและแปรคำสั่งที่ถูกเขียนไว้ในโปรแกรม
      2. ประมวลผลตามคำสั่งที่เขียนไว้ในโปแกรม
      3. รับส่งข้อมูลโดยติดต่อกับหน่วยความจำภายในเครื่อง
      4. ติดต่อรับส่งข้อมูลกับผู้ใช้ โดยผ่านหน่วยรับข้อมูลและหน่วยแสดงผล
      5. ย้ายข้อมูลและคำสั่งจากหน่วยงานหนึ่งไปยังอีกหน่วยงานหนึ่ง
## ภาษาระดับสูง (High-Level Language)
    ภาษาระดับสูง (High-Level Language) หมายถึง ภาษาที่ใช้ในการเขียนโปรแกรมที่ผู้เขียนไม่จำเป็นต้องรู้ถึงโครงสร้างภายในของเครื่องแต่อย่างใด 
    ภาษาระดับสูงมีอยู่ด้วยกันหลายภาษา เช่น ภาษาซี (C) ตรงข้ามกับภาษาแอสเซมบลี (Assembly) ซึ่งเรียกกันว่าเป็นภาษาระดับต่ำ ซึ่งต้องรู้มีความรู้พื้นฐานเกี่ยวกับ
    การทำงานของเครื่องคอมพิวเตอร์ จึงจะเขียนโปรแกรมเป็นภาษานั้นได้ อย่างไรก็ตาม คอมพิวเตอร์จะยังไม่สามารถเข้าใจภาษาระดับสูงนี้ได้แต่จะต้องใช้ตัวแปล (compiler) 
    จัดการแปล จึงจะปฏิบัติตามคำสั่งได้ 
## ภาษาแอสเซมบลี (Low-level Language)
    ภาษาแอสเซมบลี (Assembly Language) เป็นภาษาที่มีการใช้ตัวอักษรในภาษาอังกฤษมาแทนคำสั่งที่เป็นเลขฐานสอง (0,1) และเรียกอักษรสัญลักษณ์ที่เป็นคำสั่งนี้ว่า 
    สัญลักษณ์ข้อความ (mnemonic codes) เพื่อให้ง่ายต่อการเขียนและการจดจำมากกว่าภาษาเครื่อง ภาษาแอสเซมบลียังจัดเป็นภาษาระดับต่ำ (Low-level Language) 
    มีการใช้สัญลักษณ์มาใช้ในการเขียนโปรแกรม 
## ภาษาเครื่อง (Machine Language)
    ภาษาเครื่อง (Machine Language) คือ ภาษาคอมพิวเตอร์ที่สามารถทำให้เครื่องรับรู้และเข้าใจได้ เขียนโดยใช้รหัสเลขฐานสองเป็นหลัก (จะมีแต่เลข 0 กับ 1 เท่านั้น) 
    คำสั่งแต่ละคำสั่งจะหมายถึงการทำงานอย่างหนึ่ง แต่ละโปรแกรมจึงจะยาวค่อนข้างมาก
## RISC-V
### ภาษาระดับสูง (High-Level Language) : C
![image](https://user-images.githubusercontent.com/98943460/161530170-a2b9df57-97b8-4048-81a3-ac4bd3f50e1f.png)
### ภาษาแอสเซมบลี (Low-level Language) : RISC-V rv64gc clang 14.0.0
 ![image](https://user-images.githubusercontent.com/98943460/161530334-119d2821-d222-44dc-bd92-6381902937f6.png)
 ### ภาษาเครื่อง (Machine Language) : ตัวอักษรสีเทาข้างล่างภาษาแอสแซมบลี
![image](https://user-images.githubusercontent.com/98943460/161531027-196b7e03-dc01-46b7-aaa9-fb5de20f04dd.png)
![image](https://user-images.githubusercontent.com/98943460/161530825-73e818da-c98b-4c83-9d56-0e7eedfdc823.png)
## X86
### ภาษาระดับสูง (High-Level Language) : C++
![image](https://user-images.githubusercontent.com/98943460/161531611-1b9526a8-25d9-4183-b9c7-d155bbc44bdf.png)
### ภาษาแอสเซมบลี (Low-level Language) : X86-64 icx2021.4.0
![image](https://user-images.githubusercontent.com/98943460/161531840-d351682a-b410-4e6b-b9ac-d9c04824dd42.png)
### ภาษาเครื่อง (Machine Language) : ตัวอักษรสีเทาข้างล่างภาษาแอสแซมบลี
![image](https://user-images.githubusercontent.com/98943460/161532024-51ec5224-2110-4035-9552-b4d7f59ed534.png)
![image](https://user-images.githubusercontent.com/98943460/161532064-4229afcb-3e53-43da-aa97-86eeda3677ef.png)
## อ้างอิง
1. [https://www.hp.com/th-th/shop/tech-takes/post/what-is-processor-speed-and-why-does-it-matter](https://www.hp.com/th-th/shop/tech-takes/post/what-is-processor-speed-and-why-does-it-matter)
2. [https://dictionary.sanook.com/search/dict-computer/high-level-language](https://dictionary.sanook.com/search/dict-computer/high-level-language)
3. [https://milerdev.blogspot.com/2016/11/2-assembly-language.html](https://milerdev.blogspot.com/2016/11/2-assembly-language.html)
4. [https://dictionary.sanook.com/search/dict-computer/machine-language](https://dictionary.sanook.com/search/dict-computer/machine-language)
5. [https://godbolt.org/](https://godbolt.org/)
