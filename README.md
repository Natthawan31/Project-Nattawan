# FinalProject

### ความเป็นมาของโปรแกรม
=เนื่องจากการบันทึกข้อมูล และการเก็บข้อมูลไม่เป็นสัดส่วน ทำให้บางครั้งสินค้าตกหล่น เลยคิดโปรแกรมนี้ขึ้นมาเพื่อตอบสนองของผู้ใช้ที่เป็นพ่อค้าเเม่ค้าออนไลน์ เพื่อให้การเช็คออร์เดอร์ง่ายขึ้น


### วัตถุประสงค์ของโปรแกรม
=บันทึกข้อมูลของสินค้า


### โครงสร้างของโปรแกรม (Class diagram)

```mermaid
classDiagram
    Program <|-- DAEShop
    DAEShop <|-- Archlogobrushedhoodie
    DAEShop <|-- Archlogohoodzip_up
    DAEShop <|-- NesticKickFleece
    DAEShop <|-- Fadepatterncardigan
    DAEShop <|-- Splitbrushedhoodie
    DAEShop <|-- PaintPlayRaised
    DAEShop <|-- Snugoverfitfleece
    DAEShop <|-- Blockingwindbreaker
    Program : +Main()
    class DAEShop{
        +openToolStripMenuItem_Click()
        +saveToolStripMenuItem_Click()
        +button2_Click()
    }
    class Archlogobrushedhoodie{
        +getName()
        +getColor()
        +getPrice()
        
    }
    class Archlogohoodzip_up{
        +getName()
        +getColor()
        +getPrice()
    }
    class NesticKickFleece{
        +getName()
        +getColor()
        +getPrice()    
    }
    class Fadepatterncardigan{
        +getName()
        +getColor()
        +getPrice()
    }
    class Splitbrushedhoodie{
        +getName()
        +getColor()
        +getPrice()
    }
    class PaintPlayRaised{
        +getName()
        +getColor()
        +getPrice()
    }
    class Snugoverfitfleece{
        +getName()
        +getColor()
        +getPrice()
    }
    class Blockingwindbreaker{
        +getName()
        +getColor()
        +getPrice()
    }
```

### ชื่อของผู้พัฒนาโปรแกรม
653450089-1 ณัฐวรรณ พวงมะลัย
