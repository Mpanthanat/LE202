# CLIP6
## เขียนโปรแกรม แสดงตัวอักษร (ตัวย่อ ชื่อ สกุล) ตัวอย่างของผู้เขียน ชื่อ(P) นามสกุล(M)

![image](https://user-images.githubusercontent.com/98943460/160075111-4d5bcf35-294f-4dfb-95bb-d23a3ebc67a3.png)
## คำสั่งที่ 1
    คำสั่งที่ 1  addiคือการบวก เป็นการบอกให้นำเลข 32 ไปบวกกับ X0 ทางขวามือ เมื่อได้ค่าให้นำไปใส่ใน X1
   ![image](https://user-images.githubusercontent.com/98943460/160100934-c53606e9-9337-4be9-9a51-8c8ee6a45b3c.png)
## คำสั่งที่ 2
    คำสั่งที่ 2  lui(load upper immediate) เป็นการเอาค่า 0xc0000000 ไปใส่ในค่า X2 แค่ 20 bit แรก
   ![image](https://user-images.githubusercontent.com/98943460/160101532-0da3b271-1ba1-4c43-91f2-846a157a123e.png)
## คำสั่งที่ 3
    คำสั่งที่ 3  lbu(load byte unsigned) เป็นการนำค่า X1 ไป load มาแค่ 1 byte แล้วนำมาใส่ใน X3
   ![image](https://user-images.githubusercontent.com/98943460/160101878-e1b55471-a0b2-47bf-a741-a96cf767e9b5.png)
## คำสั่งที่ 4
    คำสั่งที่ 4  beq(branch if equal) เป็นการเช็คว่า  X3 = X0 ถ้าเท่ากันให้+16 แต่ถ้าไม่เท่ากันให้ไปต่อที่คำสั่ง 5
   ![image](https://user-images.githubusercontent.com/98943460/160102294-1a6b9fc9-d169-487a-81e3-055dc55bce58.png)
## คำสั่งที่ 5
    คำสั่งที่ 5  sb(store byte) นำ X2 + 0 จากนั้นนำไปใส่ที่ address แล้วจึงนำค่า X3 ไปเก็ยที่หน่วยความจำบริเวณกล่องดำซ้ายล่าง
                ซึ่งในภาพตังแรกที่เข้ามาเก็บเป็นตัว P และตัวต่อไปที่loopมาเก็บคือตัว M
   ![image](https://user-images.githubusercontent.com/98943460/160102709-55f78a5a-c928-415a-9ed7-5b56d84acbad.png)
## คำสั่งที่ 6
    คำสั่งที่ 6  เป็นการนำเอาค่า X1 + 1 จากนั้นนำไปเก็บที่ X1 ซึ่งยิ่งวนloopมากค่าX1ก็จะยิ่งเพิ่ม
   ![image](https://user-images.githubusercontent.com/98943460/160103191-4aeb7c40-4cae-4517-b290-17aa788bf589.png)
## คำสั่งที่ 7
    คำสั่งที่ 7  jal(jump and link) เป็นการjumpไปที่ตำแหน่ง -16
   ![image](https://user-images.githubusercontent.com/98943460/160103430-2dc72975-21dd-4a59-87d8-ae16538a1cfe.png)
## คำสั่งที่ 8
    คำสั่งที่ 8  เมื่อเงื่อนไขของคำสั่ง4เป็นจริงที่ก็จะวนอยู่ที่คำสั่งนี้
   ![image](https://user-images.githubusercontent.com/98943460/160075111-4d5bcf35-294f-4dfb-95bb-d23a3ebc67a3.png)
## วนloop
       หลังจากคำสั่งที่ 7 เมื่อjump ไป -16 นั่นก็คือตรงคำสั่งที่ 3 และทำต่อถึงคำสั่งที่ 4 ถ้าค่าไม่เท่ากันก็จะทำคำสั่งที่ 5 ต่อแต่ถ้ามี X3=X0 จะ+16
       หรือก็คือตำแหน่งที่คำสั่งที่ 8 จบโปรแกรม
   ![image](https://user-images.githubusercontent.com/98943460/160075111-4d5bcf35-294f-4dfb-95bb-d23a3ebc67a3.png)

 **Website [http://tice.sea.eseo.fr/riscv/](http://tice.sea.eseo.fr/riscv/)**

