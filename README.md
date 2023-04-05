# FinalProject

### ความเป็นมาของโปรแกรม
=เนื่องจากการบันทึกข้อมูล และการเก็บข้อมูลไม่เป็นสัดส่วน ทำให้บางครั้งสินค้าตกหล่น เลยคิดโปรแกรมนี้ขึ้นมาเพื่อตอบสนองของผู้ใช้ที่เป็นพ่อค้าเเม่ค้าออนไลน์ เพื่อให้การเช็คออร์เดอร์ง่ายขึ้น


### วัตถุประสงค์ของโปรแกรม
=บันทึกข้อมูลของสินค้า


### โครงสร้างของโปรแกรม (Class diagram)

```mermaid
classDiagram
    Program <|-- DAEShop
    DAEShop <|-- The Chains
    DAEShop <|-- Deeperdark Party Monstar Sleeveles
    DAEShop <|-- Deeperdark Turtle Straws
    DAEShop <|-- Life Sucks
    DAEShop <|-- Cutting Farm Hoodies
    DAEShop <|-- Deeperdark Shark Finning
    DAEShop <|-- Deeperdark Kidnapped.A.Mermaid
    DAEShop <|-- The Chains Sweater
    Program : +Main()
    class DAEShop{
        +openToolStripMenuItem_Click()
        +saveToolStripMenuItem_Click()
        +button2_Click()
    }
    class The Chains{
        +getName()
        +getColor()
        +getPrice()
        
    }
    class Deeperdark Party Monstar Sleeveles{
        +getName()
        +getColor()
        +getPrice()
    }
    class Deeperdark Turtle Straws{
        +getName()
        +getColor()
        +getPrice()    
    }
    class Life Sucks{
        +getName()
        +getColor()
        +getPrice()
    }
    class Cutting Farm Hoodies{
        +getName()
        +getColor()
        +getPrice()
    }
    class Deeperdark Shark Finning{
        +getName()
        +getColor()
        +getPrice()
    }
    class Deeperdark Kidnapped.A.Mermaid{
        +getName()
        +getColor()
        +getPrice()
    }
    class The Chains Sweater{
        +getName()
        +getColor()
        +getPrice()
    }
```

### ชื่อของผู้พัฒนาโปรแกรม
653450089-1 ณัฐวรรณ พวงมะลัย
